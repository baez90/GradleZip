FROM gradle:4.3.1-jdk8-alpine

LABEL maintainer="peter.kurfer@stud.fh-rosenheim.de"
USER root
RUN apk add --update zip tar && rm -rf /var/cache/apk/*
USER gradle
