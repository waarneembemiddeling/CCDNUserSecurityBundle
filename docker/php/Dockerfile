FROM php:7.2

# packages for symfony
RUN apt-get update && apt-get install -y zlib1g-dev libicu-dev && docker-php-ext-install pdo_mysql intl

# composer
RUN apt-get update && apt-get install git -y && curl -sS https://getcomposer.org/installer | php && mv composer.phar /usr/local/bin/composer
