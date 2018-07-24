FROM tfirdaus/wp-docklines:php5.4-fpm

LABEL Thoriq Firdaus <thoriqoe@gmail.com>

ENV REDIS_VERSION 4.1.0

RUN set -ex; \
	pecl install "redis-${REDIS_VERSION}" \
    && docker-php-ext-enable redis