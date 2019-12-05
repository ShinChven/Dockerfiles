FROM ubuntu:bionic

MAINTAINER shinchven@gmail.com

RUN curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun \
&& curl -L https://get.daocloud.io/docker/compose/releases/download/1.25.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose \
&& chmod +x /usr/local/bin/docker-compose \
&& docker --version && docker-compose --version
