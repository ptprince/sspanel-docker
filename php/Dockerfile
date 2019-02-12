FROM php:7.2-fpm-alpine

RUN apk add --no-cache libpng libpng-dev && \
    docker-php-ext-install gd && \
    docker-php-ext-install mysqli && \
    docker-php-ext-install pdo && \
    docker-php-ext-install pdo_mysql && \
    docker-php-ext-enable pdo_mysql && \
    apk del libpng-dev
