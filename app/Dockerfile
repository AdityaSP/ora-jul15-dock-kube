FROM alpine
RUN apk update
RUN apk add apache2
COPY mypage.html /var/www/localhost/htdocs
CMD ["httpd", "-D", "FOREGROUND"]
