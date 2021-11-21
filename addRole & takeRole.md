addRole:

$nomention
$argsCheck[>1;Use no formato `@menção` `@cargo`]
$title[Cargo adicionado!]
$thumbnail[$userAvatar[$mentioned[1]]]
$color[FFFFFF]
$description[<@$mentioned[1]> recebeu o cargo: <@&$mentionedRoles[1]>]
$onlyPerms[manageroles;Você não tem permissão para usar este comando!]
$onlyBotPerms[manageroles;Eu não tenho permissão para usar este comando!]
$giveRole[$mentioned[1];$mentionedRoles[1]]

takeRole:

$nomention
$argsCheck[>1;Use no formato `@menção` `@cargo`]
$title[Cargo retirado!]
$thumbnail[$userAvatar[$mentioned[1]]]
$color[FFFFFF]
$description[<@$mentioned[1]> teve o cargo <@&$mentionedRoles[1]> retirado]
$onlyPerms[manageroles;Você não tem permissão para usar este comando!]
$onlyBotPerms[manageroles;Eu não tenho permissão para usar este comando!]
$takeRole[$mentioned[1];$mentionedRoles[1]]
