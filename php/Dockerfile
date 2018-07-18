# https://hub.docker.com/_/php/
FROM php:7.2-apache
COPY php.ini /usr/local/etc/php/

# extensions manually
# ここで必要なパッケージをインストールする
#RUN apt-get update # \
#  && apt-get install -y libjpeg62-turbo-dev libpng-dev libmcrypt-dev \
#  && docker-php-ext-install pdo_mysql mysqli mbstring gd iconv mcrypt
