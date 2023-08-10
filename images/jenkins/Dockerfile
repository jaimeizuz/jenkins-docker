FROM jenkins/jenkins:alpine3.18-jdk17

USER root

RUN apk update && apk add docker docker-compose openrc && rc-update add docker boot && apk add maven && apk add git

USER jenkins