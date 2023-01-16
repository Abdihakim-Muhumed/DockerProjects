# An example Dockerfile for installing Git on debian
FROM debian:latest
LABEL maintainer="abdihakim.muhumed@student.moringaschool.com"
RUN apt-get update &&apt-get install -y git
ENTRYPOINT ["git"]
RUN echo "echo welcome to Docker!" >> /root/.bashrc
