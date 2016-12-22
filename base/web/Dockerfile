FROM node:alpine

MAINTAINER moesn <475484467@qq.com>

RUN npm install -g http-server

ADD index.html /opt/hello/

WORKDIR /opt/hello

CMD ["http-server"]