FROM php:8.2-fpm

# UPDATE APT
RUN apt-get update -y

# INSTALL EXTENSION DEPENDENCIES
RUN apt-get install -y libcurl3-dev && apt-get clean -y
RUN apt-get install -y libzip-dev
RUN apt-get install -y openssl
RUN apt-get install -y libpng-dev

# PHP EXTENSIONS
RUN docker-php-ext-install curl
RUN docker-php-ext-install gd
RUN docker-php-ext-install pdo
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install mysqli