FROM alpine:3.16
MAINTAINER SocialEngine
RUN apk add --update ca-certificates 

ADD dist/rancher-cron /usr/bin/rancher-cron

CMD ["rancher-cron"]
