registrar:

$nomention
$deletecommand
$title[ð Registre-se!]
$description[ð¹ Homem
ðº Mulher
ð« NÃ£o quero falar]
$addButton[no;ho;ð¹;secondary;no;]
$addButton[no;mu;ðº;secondary;no;]
$addButton[no;na;ð«;secondary;no;]

$onInteraction[ho]:
$nomention
$title[ð Registre-se!]
$description[ðº +18
â -18]
$addButton[no;+;ðº;secondary;no;]
$addButton[no;-;â;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO HOMEM]
$setUserVar[genero;<@&ID DO CARGO HOMEM>]

$onIntercation[mu]:

$nomention
$title[ð Registre-se!]
$description[ðº +18
â -18]
$addButton[no;+;ðº;secondary;no;]
$addButton[no;-;â;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO MULHER]
$setUserVar[genero;<@&ID DO CARGO MULHER>]

$onInteraction[na]:

$nomention
$title[ð Registre-se!]
$description[ðº +18
â -18]
$addButton[no;+;ðº;secondary;no;]
$addButton[no;-;â;secondary;no;]
$removeComponent[ho;]
$removeComponent[mu;]
$removeComponent[na;]
$giveRole[$authorID;ID DO CARGO NÃO QUERO FALAR]
$setUserVar[genero;<@&ID DO CARGO NÃO QUERO FALAR>]

$onInteraction[+]:

$nomention
$title[â Registrado feito com sucesso!]
$description[VocÃª foi registrado com secesso!

Cargos recebidos: $getUserVar[genero], <@&ID DO CARGO +18>.]
$color[FFFFFF]
$giveRole[$authorID;ID DO CARGO +18]
$removeButtons

$onInteraction[-]:

$nomention
$title[â Registrado feito com sucesso!]
$description[VocÃª foi registrado com secesso!

Cargos recebidos: $getUserVar[genero], <@&ID DO CARGO -18>.]
$color[FFFFFF]
$giveRole[$authorID;ID DO CARGO -18]
$removeButtons
