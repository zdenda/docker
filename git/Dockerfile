# Debian with Git and some network/web utilities

FROM zdenda/net-utils

MAINTAINER Zdenda Kořán <zkoran@gmail.com>

RUN apt-get update \
      && apt-get install -y --no-install-recommends \
        git \
        ssh-client \
      && rm -rf /var/lib/apt/lists/*

