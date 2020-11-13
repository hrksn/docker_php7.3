FROM php:7.3-apache
COPY conf/php.ini /usr/local/etc/php/conf.d/

RUN apt-get update && \
    docker-php-ext-install mysqli