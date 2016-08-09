FROM ubuntu:16.04
MAINTAINER James Turnbull "ytfei01@foxmail.com"
ENV REFRESHED_AT 2016-08-09

RUN apt-get -yqq update && apt-get -yqq install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis

RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD [ "/opt/webapp/bin/webapp" ]
