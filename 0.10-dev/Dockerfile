FROM bilxio/ubuntu:precise

MAINTAINER Bill.Xiong<haibxz@gmail.com>

RUN curl -sL https://deb.nodesource.com/setup_0.10 | bash -
RUN apt-get install -y curl nodejs && \
    npm install -g pm2 node-inspector http-server \
    gulp-cli bower coffeelint browserify jshint jsonlint nodemon \
    bunyan semver jasmine-node mocha

EXPOSE 3000
