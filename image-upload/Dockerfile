FROM ubuntu:20.04

RUN set -x \
  && apt-get update \
  && apt-get install --no-install-recommends --no-install-suggests -y \
  devscripts \
  lintian \
  fakeroot \
  apt-utils \
  strace \
  bash \
  gnupg2 \
  openjdk-11-jdk \
  libcurl4-openssl-dev \
  libprotobuf-dev \
  protobuf-compiler \
  libtool \
  build-essential software-properties-common

RUN set -x \
  && apt-get install -y \
  vim \
  curl \
  wget