FROM alpine:latest

MAINTAINER @mateusmantoan

LABEL Description="snort IDS"

RUN apk add -u snort && rm -f /var/cache/apk/*

ENTRYPOINT squid -NYCd 1


