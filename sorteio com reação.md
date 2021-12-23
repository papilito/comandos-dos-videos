$nomention
$onlyIf[$message[1]!=;:x: Você precisa escrever o que será sorteado!]
 
$onlyIf[$replaceText[$replaceText[$replaceText[$replaceText[%$checkContains[&&&$message[1];&&&1;&&&2;&&&3;&&&4]%;%true%;$message[1]%;1];%false%;5;1];s%;;1];m%;;1]<41;:x: O tempo máximo é 41m!]
 
$onlyPerms[manageserver;:x: Você precisa da permissão de GERENCIAR SERVIDOR para sortear algo!]
 
$onlyIf[$getUserVar[gw1;$serverOwner]==0;:x: Encerre o antigo sorteio, com (seu prefixo)end <ID da msg>, para iniciar outro sorteio!]
$author[🎉 NOVO SORTEIO]
$description[**🎊 Sorteio:** $replaceText[$replaceText[%$checkCondition[$message[2]==]%;%false%;$replaceText[$message;$message[1]; ;1];1];%true%;$message;1]
**⏰ Tempo:** $replaceText[$replaceText[$replaceText[$replaceText[%$checkContains[$message[1];m;s;1m;2m;3m;4m;5m;6m;7m;8m;9m;0m;1s;2s;3s;4s;5s;6s;7s;8s;9s;0s]$checkContains[%$message[1];%1;%2;%3;%4;%5;%6;%7;%8;%9]%;%truetrue%;$message[1];1];%falsefalse%;Não especificado;1];%falsetrue%;Not defined;1];%truefalse%;Not defined;1]
**🥳 Ganhador:** Por enquanto ninguém!]
$footer[Reaja com 🎉 para entrar no sorteio!]
$color[ff0000]
$addReactions[🎉]
$setUserVar[gw1;$replaceText[$replaceText[%$checkCondition[$message[2]==]%;%false%;$replaceText[$message;$message[1]; ;1];1];%true%;$message;1];$serverOwner]
 
$setUserVar[gw3;$$replaceText[$replaceText[$replaceText[$replaceText[%$checkContains[$message[1];m;s;1m;2m;3m;4m;5m;6m;7m;8m;9m;0m;1s;2s;3s;4s;5s;6s;7s;8s;9s;0s]$checkContains[%$message[1];%1;%2;%3;%4;%5;%6;%7;%8;%9]%;%truetrue%;editEmbedIn;1];%falsefalse%;checkContains;1];%falsetrue%;checkContains;1];%truefalse%;checkContains;1][$replaceText[$replaceText[$replaceText[$replaceText[%$checkContains[$message[1];m;s;1m;2m;3m;4m;5m;6m;7m;8m;9m;0m;1s;2s;3s;4s;5s;6s;7s;8s;9s;0s]$checkContains[%$message[1];%1;%2;%3;%4;%5;%6;%7;%8;%9]%;%truetrue%;$message[1];1];%falsefalse%;NoN;1];%falsetrue%;NoN;1];%truefalse%;NoN;1];⏰ Sorteio encerrado;Para saber quem ganhou, algum staff deverá utilizar (seu prefixo)end; ;FFE4C4]]
$varExistError[gw1;Crie uma variável chamada gw1, e coloque o valor como 0]
$varExistError[gw2;Crie uma variável chamada gw2, e coloque o valor como 0]
$varExistError[gw3;Crie uma variável chamada gw3, e coloque o valor como 0]
