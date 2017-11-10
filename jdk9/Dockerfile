FROM gradle:4.3.0-jdk9

LABEL maintainer="peter.kurfer@stud.fh-rosenheim.de"
USER root
RUN apk add --update zip tar && rm -rf /var/cache/apk/*
USER gradle