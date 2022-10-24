FROM nginx:1.22

WORKDIR /var/www/static/

COPY ["nginx.conf", "/etc/nginx/nginx.conf"]

COPY ["index.html", "jquery.min.js", "style.css", "./"]

