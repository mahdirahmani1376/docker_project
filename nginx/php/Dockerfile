FROM php:8.3-fpm

RUN docker-php-ext-install pdo pdo_mysql

#RUN apt-get update && apt-get install -y unzip \
#&& docker-php-ext-install pdo_mysql php-cli
# Install Composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

WORKDIR /var/www/html

RUN chown -R www-data:www-data .
