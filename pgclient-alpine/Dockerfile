FROM alpine

RUN apk update 
RUN apk add postgresql-client
RUN rm -rf /var/cache/apk/*

# docker build -t pgclient:alpine .