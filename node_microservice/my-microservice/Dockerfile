FROM ubuntu:latest
MAINTAINER blueoasis

RUN apt-get update
RUN apt-get install nodejs nodejs-legacy npm -y
RUN apt-get clean

COPY ./package.json src/

RUN cd src && npm install

COPY . /src

WORKDIR src/

CMD ["npm","start"]
