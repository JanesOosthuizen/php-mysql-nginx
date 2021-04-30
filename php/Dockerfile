FROM php:7.4.13-fpm-alpine

RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
CMD ["php-fpm"]

EXPOSE 9000