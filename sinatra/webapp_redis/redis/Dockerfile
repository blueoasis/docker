FROM ubuntu:16.04
MAINTAINER Jason
ENV REFRESHED_AT 2017-02-21

RUN apt-get update && apt-get -y install redis-server redis-tools

EXPOSE 6379
ENTRYPOINT ["/usr/bin/redis-server"]
CMD []
