FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

RUN \
    apt-get -y update && \
    apt-get -y dist-upgrade && \
    apt-get -y install build-essential yasm nasm pkg-config git curl wget cmake unzip subversion autoconf automake libtool clang && \
    apt-get -y clean