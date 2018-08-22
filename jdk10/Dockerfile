FROM gradle:4.9.0-jdk10-slim

LABEL maintainer="peter.kurfer@stud.fh-rosenheim.de"
USER root
RUN apt-get update && \
    apt-get install -y zip && \
    rm -rf /var/lib/apt/lists/*
USER gradle
