FROM fedora:42

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    dnf update -y && \
    dnf install -y gawk gcc mpdecimal-devel python3 python3-libselinux python3-libdnf5 python3-devel sudo

ENV SHELL=/bin/bash
