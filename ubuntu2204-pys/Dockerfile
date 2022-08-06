FROM ubuntu:22.04

RUN \
    apt update -y && \
    apt install -y apt-utils gcc git python3 python3-dev python3-pip libssl-dev sudo && \
    ln -s /usr/bin/python3 /usr/bin/python && \
	rm -rf /var/lib/apt/lists/*

ENV SHELL /bin/bash
