FROM tfirdaus/wp-docklines:php7.3-fpm

LABEL Thoriq Firdaus <thoriqoe@gmail.com>

ENV REDIS_VERSION 5.3.2

RUN set -ex; \
	pecl install "redis-${REDIS_VERSION}" \
    && docker-php-ext-enable redis
