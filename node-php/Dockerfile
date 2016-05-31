FROM ubuntu:latest

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get dist-upgrade -y \
  && apt-get install -y git git-core wget curl zip unzip nano build-essential xvfb \
  && apt-get install -y nodejs npm \
  && apt-get install -y php7.0-sqlite php7.0-curl php7.0-gd php7.0-gmp php7.0-mcrypt php7.0-intl php7.0-dev php7.0-xsl php7.0-xml php7.0-bcmath php-pear \
  && apt-get autoclean && apt-get --purge -y autoremove && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
