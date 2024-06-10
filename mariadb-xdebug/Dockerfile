FROM matomo:latest

RUN apt-get update && \
    apt-get install -y php-xdebug && \
    docker-php-ext-enable xdebug

COPY xdebug.ini /usr/local/etc/php/conf.d/

EXPOSE 9000