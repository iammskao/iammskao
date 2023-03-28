
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://iammskao.github.io/iammskao/index.html$1 [R,L]
