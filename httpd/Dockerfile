FROM alpine

RUN apk update
RUN apk add apache2
RUN apk add apache2-utils

COPY index.html /var/www/localhost/htdocs/index.html 

EXPOSE 80

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
