FROM rockylinux/rockylinux:9

LABEL maintainer="Nicola Musatti <nicola.musatti@gmail.com>"

RUN \
    dnf update -y && \
    dnf install -y gcc git openssl-devel python3 python3-libselinux python3-devel sudo systemd systemd-libs systemd-pam nmap-ncat bind-utils && \
    ln -s /usr/bin/python3 /usr/bin/python && \
    dnf clean all && \
    rm -rf /var/cache/dnf/*

ENV SHELL=/bin/bash