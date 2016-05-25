FROM ubuntu:xenial

RUN apt update \
 && apt install -y --allow-downgrades --allow-remove-essential --allow-change-held-packages --no-install-recommends\
      apt-transport-https \
      ssh-client \
      build-essential \
      curl \
      ca-certificates \
      git \
      libicu-dev \
      lsb-release \
      python-all \
      rlwrap \
 && rm -rf /var/lib/apt/lists/*;