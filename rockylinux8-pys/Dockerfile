FROM rockylinux/rockylinux:8

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    dnf update -y && \
    dnf install -y gcc git openssl-devel python3 python3-libselinux python3-devel python3-virtualenv sudo nmap-ncat bind-utils && \
    ln -s /usr/bin/python3 /usr/bin/python && \
    dnf clean all && \
    rm -rf /var/cache/dnf/*

ENV SHELL=/bin/bash