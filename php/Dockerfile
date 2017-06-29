FROM php:apache

RUN apt-get update && apt-get upgrade -y
RUN docker-php-ext-install mysqli
RUN docker-php-ext-install pdo_mysql

COPY index.php /var/www/html/