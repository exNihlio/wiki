FROM ubuntu:22.04
ENV debian-frontend=non-interactive

RUN apt-get -y update && \
    apt-get -y install lib32gcc1

EXPOSE 27015/udp
EXPOSE 27020/tcp
EXPOSE 7777/udp
EXPOSE 7778/udp
