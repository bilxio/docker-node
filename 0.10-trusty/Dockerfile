FROM tutum/ubuntu:trusty

MAINTAINER Bill.Xiong<haibxz@gmail.com>

# install curl
RUN apt-get update && apt-get install -y curl

# install NodeJS source
RUN curl -sL https://deb.nodesource.com/setup_0.10 | bash -

# install NodeJS & global npm modules
RUN apt-get update && apt-get install -y nodejs

EXPOSE 3000
