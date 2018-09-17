FROM php:5.6.33-fpm-alpine3.4
RUN docker-php-ext-install mysqli pdo_mysql
RUN apk add --no-cache --virtual libxml2-dev
RUN docker-php-ext-install soap
RUN apk add --no-cache --virtual freetype-dev libjpeg-turbo-dev libmcrypt-dev libpng-dev
RUN docker-php-ext-install gd
RUN docker-php-ext-install opcache