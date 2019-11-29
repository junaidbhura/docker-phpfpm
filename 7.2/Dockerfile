FROM 10up/phpfpm:7.2

RUN docker-php-ext-configure opcache --enable-opcache \
    && docker-php-ext-install opcache

# Copy configuration
COPY ./opcache.ini $PHP_INI_DIR/conf.d/
