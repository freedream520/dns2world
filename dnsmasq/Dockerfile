FROM ubuntu:14.04
MAINTAINER imlonghao <imlonghao@gmail.com>
RUN apt-get update
RUN apt-get install -y dnsmasq
RUN apt-get clean
CMD ["/usr/sbin/dnsmasq","-d"]
