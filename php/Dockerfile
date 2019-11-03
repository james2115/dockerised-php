FROM php:fpm
              
RUN apt-get update \
    && apt-get install -y iputils-ping \
    && docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable mysqli
