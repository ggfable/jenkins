FROM jenkinsci/blueocean

USER root

RUN apk add --no-cache cargo python3-dev py3-pip libffi-dev openssl-dev gcc libc-dev make \
    && pip3 install docker-compose

USER jenkins