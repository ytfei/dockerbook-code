FROM ytfei/ubuntu:16.04
MAINTAINER Evans Yang "ytfei01@foxmail.com"
ENV REFRESHED_AT 2016-08-09

RUN apt-get -yqq update && apt-get -yqq install redis-server redis-tools

EXPOSE 6379

ENTRYPOINT ["/usr/bin/redis-server"]
CMD []
