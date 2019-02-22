FROM php:7.0-fpm-alpine

RUN apk add --update --no-cache bash \
&& deluser www-data \
&& addgroup -g 101 -S www-data

RUN  adduser -u 102 -D -S www-data -G www-data

COPY php7.0.ini /usr/local/etc/php/php.ini
