FROM python:2.7

MAINTAINER Evans Yang "ytfei01@foxmail.com"
ENV REFRESHED_AT 2016-08-09

# customize python with db drivers

RUN apt-get update && apt-get install -y \
        gcc \
        gettext \
        mysql-client libmysqlclient-dev \
        postgresql-client libpq-dev \
        sqlite3 \
    --no-install-recommends && rm -rf /var/lib/apt/lists/*

