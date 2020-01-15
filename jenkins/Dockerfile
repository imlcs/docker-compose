From jenkins:latest

#声明dockerfile维护者的邮箱
LABEL maintainer "liuchengsheng95@qq.com"

USER root

RUN apt update && apt install rsync -y
WORKDIR /var/jenkins_home
