FROM quay.io/centos/centos:stream10

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    dnf update -y && \
    dnf install -y gcc git openssl-devel python3 python3-libselinux python3-devel sudo systemd systemd-libs systemd-pam nmap-ncat bind-utils && \
    dnf clean all && \
    rm -rf /var/cache/dnf/*

ENV SHELL=/bin/bash