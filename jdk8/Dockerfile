FROM gradle:4.9.0-jdk8-alpine

LABEL maintainer="peter.kurfer@stud.fh-rosenheim.de"
USER root
RUN apk add --update zip tar && rm -rf /var/cache/apk/*
USER gradle
