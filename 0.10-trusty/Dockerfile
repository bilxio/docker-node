FROM tutum/ubuntu:trusty

MAINTAINER Bill.Xiong<haibxz@gmail.com>

RUN curl -sL https://deb.nodesource.com/setup_0.10 | bash -

# install softwares
RUN apt-get update && apt-get install -y curl nodejs

# global npm modules
RUN npm install -g pm2 node-inspector http-server \
    gulp-cli bower coffeelint browserify jshint jsonlint nodemon \
    bunyan semver jasmine-node mocha

EXPOSE 3000
