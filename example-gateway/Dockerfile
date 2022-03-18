FROM nginx

COPY ./nginx.conf /etc/nginx/conf.d/default.conf
COPY ./templates  /etc/nginx/templates
COPY ./index.html /usr/share/nginx/html/index.html

EXPOSE 80
EXPOSE 443