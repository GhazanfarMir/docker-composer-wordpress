FROM wordpress:latest

LABEL maintainer="GhazanfarMir@gmail.com"

ENV APACHE_DOCUMENT_ROOT /var/www/html

RUN apt-get update && apt-get install -y apt-utils vim

COPY config/php/php.ini /usr/local/etc/php/
COPY config/apache/vhost.conf /etc/apache2/sites-available/000-default.conf
