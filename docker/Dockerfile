FROM centos:centos7.7.1908

MAINTAINER Chad J. Hamilton <chad.j.hamilton@gmail.com>

RUN yum update -y

COPY openhab.repo /etc/yum.repos.d/openhab.repo

RUN yum install -y openhab2 && \
    systemctl enable openhab2.service



