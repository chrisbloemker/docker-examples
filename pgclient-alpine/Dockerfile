FROM alpine

RUN apk update 
RUN apk add postgresql-client
RUN apk add --no-cache bash
RUN rm -rf /var/cache/apk/*

ADD motd /etc/motd
ADD profile /etc/profile

CMD ["/bin/sh", "-l"]
# docker build -t pgclient:alpine .
