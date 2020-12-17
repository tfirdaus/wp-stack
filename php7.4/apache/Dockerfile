FROM tfirdaus/wp-docklines:php7.2-apache

LABEL org.opencontainers.image.source https://github.com/tfirdaus/wp-stack

ENV REDIS_VERSION 5.3.2

RUN set -ex; \
	pecl install "redis-${REDIS_VERSION}" \
    && docker-php-ext-enable redis
