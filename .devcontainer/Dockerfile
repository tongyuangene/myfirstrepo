FROM ubuntu:jammy

LABEL version="1.0" maintainer="docker user <wangtongbgi@163.com>"

USER wangtong

RUN echo Flyto2012 | passwd --stdin wangtong

RUN apt update 

RUN apt install -y git vim tree screen htop cmake lftp lrzsz parallel tmux

RUN  echo 'export PS1="\[\e[31;1m\]\u\[\e[0m\] \[\e[32;1m\]\t \[\e[0m\]\[\e[34;1m\]\w\[\e[0m\]\n\[\e[31;1m\]$ \[\e[0m\]"' >>/root/.bashrc 

RUN apt install -y bwa samtools bcftools ncbi-blast+

