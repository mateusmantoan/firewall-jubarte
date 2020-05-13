FROM alpine:latest

MAINTAINER @mateusmantoan

RUN apk add -u squid && rm -f /var/cache/apk/*

LABEL Description="squid proxy"

VOLUME /etc/jubarte/

EXPOSE 80

CMD squid
