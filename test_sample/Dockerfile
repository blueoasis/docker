FROM ubuntu:16.04
MAINTAINER jason
ENV REFRESHED_AT 2017_02_21
RUN apt-get -yqq update; apt-get install -yqq nginx
RUN mkdir -p /var/www/html/website
ADD global.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
