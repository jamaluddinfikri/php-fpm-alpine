FROM php:5.6-fpm-alpine

RUN apk add --update --no-cache bash \
&& deluser www-data \
&& addgroup -g 101 -S www-data

RUN  adduser -u 102 -D -S www-data -G www-data

COPY php5.6.ini /usr/local/etc/php/php.ini
