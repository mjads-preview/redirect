///// INSTRUCOES RAPIDAS /////

Este projeto e uma pagina de redirecionamento para WhatsApp com rastreamento via GTM.

ALTERE ESTES CAMPOS EM index.html

No bloco com o comentario "ALTERE AQUI", ajuste:

1. whatsappPhone
Numero do WhatsApp no formato internacional, sem +, espacos ou simbolos.
Exemplo: 5511999999999

2. gtmId
ID do Google Tag Manager.
Exemplo: GTM-ABC12345

3. companyName
Nome da empresa.

4. companyLogo
Nome ou caminho do arquivo da logo.
Exemplo: logo.png

///// EVENTO PERSONALIZADO DISPARADO /////

whatsapp_redirect

///// MODO DE TESTE /////

Use o parametro abaixo no final da URL:

?debug_redirect=1

Exemplo:
http://127.0.0.1:5500/index.html?debug_redirect=1

OU

file:///C:/Users/Admin/Desktop/redirect/index.html?debug_redirect=1

^^^^ A FORMA DE ACESSO ACIMA, SÓ FUNCIONA DE A PASTA "REDIRECT" ESTIVER NA SUA AREA DE TRABALHO ^^^^

///// COMO FUNCIONA /////

Quando ?debug_redirect=1 esta na URL, a pagina nao redireciona automaticamente para o WhatsApp.
Isso serve para visualizar a pagina e testar o disparo das tags sem sair dela.
