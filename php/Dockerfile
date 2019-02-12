FROM php:7.2-fpm-alpine

RUN apk add --no-cache libpng libpng-dev && docker-php-ext-install gd && docker-php-ext-install mysqli && apk del libpng-dev
