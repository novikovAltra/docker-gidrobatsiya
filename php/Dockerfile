FROM php:7.1-fpm
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Увеличение лимита памяти
RUN echo "memory_limit=512M" > /usr/local/etc/php/conf.d/memory-limit.ini