FROM debian:buster-slim

ENV DEBIAN_VERSION=buster
ENV GCC_VERSION=5-2015-q1

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
  && apt-get install -y build-essential cmake software-properties-common clang-tidy \
  gcc-arm-none-eabi=15:${GCC_VERSION}-*

RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
