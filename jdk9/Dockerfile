FROM gradle:4.3.1-jdk9

LABEL maintainer="peter.kurfer@stud.fh-rosenheim.de"
USER root
RUN apt-get update && \
    apt-get install -y zip && \
    rm -rf /var/lib/apt/lists/*
USER gradle
