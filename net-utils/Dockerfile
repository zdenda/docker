# Debian with some network/web utilities

FROM debian:jessie

MAINTAINER Zdenda Kořán <zkoran@gmail.com>

RUN apt-get update \
      && apt-get install -y --no-install-recommends \
        dnsutils \
        ca-certificates \
        curl \
        wget \
      && rm -rf /var/lib/apt/lists/*

