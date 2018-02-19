FROM ubuntu:16.04
MAINTAINER Jason Carps "jason@example.com"
RUN ["apt-get","update","-yqq"]
RUN ["apt-get","install", "-y", "nginx"]
RUN echo 'Hello, I am your container' > /var/www/html/index.html
EXPOSE 80
#RUN ["nginx","-g","daemon off;"]
