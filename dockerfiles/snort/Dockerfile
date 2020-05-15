FROM alpine:latest

MAINTAINER @mateusmantoan

LABEL Description="squid proxy"

RUN apk add -u snort && rm -f /var/cache/apk/*

ENTRYPOINT ["squid -NYCd 1"]


