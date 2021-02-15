FROM arm32v7/alpine

MAINTAINER @mateusmantoan

RUN apk add -u tcpdump && rm -f /var/cache/apk/*

LABEL Description="sniffer"

VOLUME /etc/jubarte/ 

EXPOSE 80

