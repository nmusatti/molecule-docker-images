FROM centos:7
LABEL maintainer Nicola Musatti <nicola.musatti@gmail.com>

RUN \
    yum update -y && \
    yum install -y gcc git openssl-devel python libselinux-python python-devel python-virtualenv sudo nmap-ncat bind-utils && \
    yum clean all && \
    rm -rf /var/cache/yum/*

ENV SHELL /bin/bash
