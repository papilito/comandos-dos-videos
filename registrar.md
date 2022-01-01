registrar:

$nomention
$deletecommand
$title[📃 Registre-se!]
$description[🚹 Homem
🚺 Mulher
🚫 Não quero falar]
$addButton[no;ho;🚹;secondary;no;]
$addButton[no;mu;🚺;secondary;no;]
$addButton[no;na;🚫;secondary;no;]

$onInteraction[ho]:
$nomention
$title[📃 Registre-se!]
$description[🍺 +18
☕ -18]
$addButton[no;+;🍺;secondary;no;]
$addButton[no;-;☕;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO HOMEM]
$setUserVar[genero;<@&ID DO CARGO HOMEM>]

$onIntercation[mu]:

$nomention
$title[📃 Registre-se!]
$description[🍺 +18
☕ -18]
$addButton[no;+;🍺;secondary;no;]
$addButton[no;-;☕;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO MULHER]
$setUserVar[genero;<@&ID DO CARGO MULHER>]

$onInteraction[na]:

$nomention
$title[📃 Registre-se!]
$description[🍺 +18
☕ -18]
$addButton[no;+;🍺;secondary;no;]
$addButton[no;-;☕;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO NÃO QUERO FALAR]
$setUserVar[genero;<@&ID DO CARGO NÃO QUERO FALAR>]

$onInteraction[+]:

$nomention
$title[✅ Registrado feito com sucesso!]
$description[Você foi registrado com secesso!

Cargos recebidos: $getUserVar[genero], <@&ID DO CARGO +18>.]
$color[FFFFFF]
$giveRole[$authorID;ID DO CARGO +18]
$removeButtons

$onInteraction[-]:

$nomention
$title[✅ Registrado feito com sucesso!]
$description[Você foi registrado com secesso!

Cargos recebidos: $getUserVar[genero], <@&ID DO CARGO -18>.]
$color[FFFFFF]
$giveRole[$authorID;ID DO CARGO -18]
$removeButtons
