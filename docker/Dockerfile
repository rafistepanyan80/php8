FROM php:8.1.0-fpm

ENV TZ=Europe/Sofia

RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt update && apt install -y git curl wget zip unzip nano

WORKDIR /var/www
