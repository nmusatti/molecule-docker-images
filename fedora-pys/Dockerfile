FROM fedora:latest
LABEL maintainer Nicola Musatti <nicola.musatti@gmail.com>

RUN \
    dnf update -y && \
    dnf install -y gcc python3 python3-libselinux python3-devel sudo && \
    ln -s /usr/bin/python3 /usr/bin/python

ENV SHELL /bin/bash