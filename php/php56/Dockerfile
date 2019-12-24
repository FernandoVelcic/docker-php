FROM php:5.6-fpm-alpine

# Packages install
# lbmcrypt-dev (system)
RUN apk add libmcrypt-dev

# pdo, pdo_mysql, mcrypt (php-ext)
RUN docker-php-ext-install pdo pdo_mysql mcrypt