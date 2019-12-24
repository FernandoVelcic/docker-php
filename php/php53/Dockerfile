FROM devilbox/php-fpm-5.3:latest

# Install libmcrypt headers
RUN apt-get update && apt-get install -y libmcrypt-dev

# pdo, pdo_mysql, mcrypt (php-ext)
RUN docker-php-ext-install pdo pdo_mysql mcrypt