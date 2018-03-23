FROM openjdk:8u131-jdk-alpine

LABEL Description="cerebro for elasticsearch" MAINTAINER="xuanye.wan@gmail.com"

ENV VERSION 0.7.2

RUN apk add --no-cache bash

WORKDIR /app
COPY ./0.7.2 ./

EXPOSE 9000

ENTRYPOINT [ "./bin/cerebro" ]