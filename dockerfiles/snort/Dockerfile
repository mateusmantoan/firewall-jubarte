FROM alpine:latest

MAINTAINER @mateusmantoan

LABEL Description="squid IDS"

RUN apk add -u snort && rm -f /var/cache/apk/*

VOLUME /etc/

VOLUME /var/log/

EXPOSE 80

