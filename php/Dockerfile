FROM php:7.4.29-apache

RUN docker-php-ext-install mysqli pdo pdo_mysql

# Apache mod_rewrite aktif et
RUN a2enmod rewrite

# Varsayılan dizini ayarla
WORKDIR /var/www/html

# Gerekli PHP ayarları için (isteğe bağlı)
COPY ./php.ini /usr/local/etc/php/
