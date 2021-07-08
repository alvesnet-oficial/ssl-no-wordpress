# ssl-no-wordpress

Instalar o plugin seguinte plugin:

- WP Encryption – One Click Free SSL Certificate & SSL / HTTPS Redirect to fix Insecure Content (Por Por Go Web Smarty)

* Ele é compative com o certificado SSL Let's Encrypt


Caso ao tentar ativar o SSL e ficar sem acesso a pagina do Wordpress altere a seguintes linhas no banco de dados do wordpress na tabela wp_options:


siteurl: https://www.seudominio.com.br
home: https://www.seudominio.com.br


Para:

siteurl: http://www.seudominio.com.br
home: http://www.seudominio.com.br

Apos alterar os parametros acima seu site vai voltar a funcionar somente com o http:// e permitira que entra no painel do wordpress
