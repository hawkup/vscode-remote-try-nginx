# VSCode Remote Try Nginx

<p>
    <a href="https://online.visualstudio.com/environments/new?name=VSCode%20Remote%20Try%20Nginx&repo=hawkup/vscode-remote-try-nginx">
        <img src="https://img.shields.io/endpoint?style=social&url=https%3A%2F%2Faka.ms%2Fvso-badge">
    </a>
</p>

* cp default.conf /etc/nginx/conf.d/
* cp index.html /usr/share/nginx/html/
* `nginx` start nginx
* `nginx -t` verify nginx config
* `nginx -s reload` apply new config
