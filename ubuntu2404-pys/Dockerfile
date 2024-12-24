FROM ubuntu:24.04

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    apt update -y && \
    apt install -y apt-utils gcc git python3 python3-dev python3-pip libssl-dev sudo && \
    ln -s /usr/bin/python3 /usr/bin/python && \
	rm -rf /var/lib/apt/lists/*

ENV SHELL=/bin/bash
