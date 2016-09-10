FROM ubuntu:14.04
MAINTAINER Romanos Skiadas <rom.skiad@gmail.com>

RUN apt-get update
RUN apt-get -y install createrepo rpm dpkg-dev python-pip ruby ruby-dev wget git
RUN gem install fpm
RUN pip install fuel-plugin-builder
