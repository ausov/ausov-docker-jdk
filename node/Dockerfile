#
# CI builder image template with development tools:
# PHP 7, Oracle JDK 8, Node.js, Python, Ruby, etc.
#

FROM ubuntu:latest

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get dist-upgrade -y \
  && apt-get install -y git git-core wget curl zip unzip nano build-essential xvfb \
  && apt-get install -y nodejs npm \
  && apt-get autoclean && apt-get --purge -y autoremove && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
