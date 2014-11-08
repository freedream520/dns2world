FROM ubuntu:precise
MAINTAINER imlonghao <imlonghao@gmail.com>
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update
RUN apt-get -y install python-software-properties
RUN add-apt-repository ppa:dlundquist/sniproxy
RUN apt-get update
RUN apt-get -y install sniproxy
RUN apt-get clean
CMD ["/usr/sbin/sniproxy","-f"]
