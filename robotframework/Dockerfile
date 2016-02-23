FROM ubuntu:latest

MAINTAINER Ludovic Meurillon <ludovic.meurillon@orange.com>

RUN apt-get -y update \
    && apt-get install -y python python-pip \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN pip install robotframework
RUN pip install robotframework-selenium2library
RUN pip install robotframework-faker

RUN     mkdir /robot
VOLUME  /robot
WORKDIR /robot
