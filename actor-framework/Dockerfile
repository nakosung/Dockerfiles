FROM ubuntu:14.04

MAINTAINER deif79@gmail.com

RUN apt-get update -y
RUN apt-get install build-essential cmake git -y
RUN apt-get install libprotobuf-dev libpthread-stubs0-dev -y
RUN git clone https://github.com/actor-framework/actor-framework.git
RUN cd actor-framework; ./configure && make && make install
ENV LD_LIBRARY_PATH /usr/local/lib:${LD_LIBRARY_PATH}
