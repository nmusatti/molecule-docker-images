FROM fedora:41

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    dnf update -y && \
    dnf install -y gcc python3 python3-libselinux python3-devel sudo

ENV SHELL=/bin/bash
