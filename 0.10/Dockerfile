FROM tutum/ubuntu:precise

MAINTAINER haibxz@gmail.com

RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_0.10 | bash -
RUN apt-get install -y nodejs

EXPOSE 3000
