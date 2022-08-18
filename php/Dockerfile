ARG PHP_VERSION

FROM php:${PHP_VERSION} AS base

###

FROM base AS build

COPY --from=composer /usr/bin/composer /usr/bin/composer
