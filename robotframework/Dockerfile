FROM ubuntu:latest

MAINTAINER Ludovic Meurillon <ludovic.meurillon@gmail.com>

RUN apt-get -y update \
    && apt-get install -y python python-pip \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN pip install robotframework==2.8.7
RUN pip install robotframework-selenium2library==1.7.0