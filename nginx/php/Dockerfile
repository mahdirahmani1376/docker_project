FROM php:8.3-fpm

RUN mkdir /var/www/html/public

RUN docker-php-ext-install pdo pdo_mysql

CMD ["php-fpm","-y","/usr/local/etc/php-fpm.conf","-R"]