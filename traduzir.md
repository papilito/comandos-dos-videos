$nomention
$deletecommand
$argsCheck[>1;Escreva algo em inglês para traduzir!]
$title[Tradutor]
$description[Palavra(s): $message

Tradução: $httpResult[translated;text]
$httpGet[https://translate-api.ml/translate?text=$replaceText[$message; ;+;-1]&lang=pt]]
$footer[Pedido por: $username]
