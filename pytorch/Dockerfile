FROM floydhub/pytorch:0.3.0-gpu.cuda9cudnn7-py3.22
MAINTAINER deif79@gmail.com

RUN echo "deb https://dl.bintray.com/wangzw/deb trusty contrib" | tee /etc/apt/sources.list.d/bintray-wangzw-deb.list
RUN apt-get install -y apt-transport-https
RUN apt-get update -y
RUN apt-get install -y libhdfs3 libhdfs3-dev
