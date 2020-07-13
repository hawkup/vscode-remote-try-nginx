# VSCode Remote Try Nginx

cp default.conf /etc/nginx/conf.d/
cp index.html /usr/share/nginx/html/
`nginx` start nginx
`nginx -t` verify nginx config
`nginx -s reload` apply new config
