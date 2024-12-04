FROM ubuntu:jammy

LABEL version="1.0" maintainer="docker user <wangtongbgi@163.com>"

USER wangtong

RUN echo Flyto2012 | passwd --stdin wangtong

RUN apt update 

RUN apt install -y git vim tree screen htop cmake lftp lrzsz parallel tmux
