FROM php:8-fpm-alpine

COPY --from=composer /usr/bin/composer /usr/bin/composer


RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN docker-php-ext-install mysqli

RUN apk add --update nodejs npm
RUN apk add --update npm
