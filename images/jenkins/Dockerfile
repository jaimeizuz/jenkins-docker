FROM jenkins/jenkins:2.457-alpine-jdk21

USER root

RUN apk update && apk add docker docker-compose openrc && rc-update add docker boot && apk add maven && apk add git

USER jenkins