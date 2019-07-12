FROM ubuntu:19.04
ENV BUILD_DATE 20190712
RUN apt update && apt upgrade -y && apt install -y \
      bash-completion \
      curl \
      git \
      jq \
      httpie \
      less \
      subversion \
      wget \
    && rm -rf /var/lib/apt/lists/*
CMD /bin/bash