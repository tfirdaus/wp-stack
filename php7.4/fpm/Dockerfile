FROM tfirdaus/wp-docklines:php7.4-fpm

LABEL org.opencontainers.image.source https://github.com/OWNER/REPO

ENV REDIS_VERSION 5.3.2

RUN set -ex; \
	pecl install "redis-${REDIS_VERSION}" \
    && docker-php-ext-enable redis \
	&& rm -rf /var/lib/apt/lists/*
