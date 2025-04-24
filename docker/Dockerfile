### STAGE 1: Build ###
FROM node:16.20.2 AS build
RUN apt-get update -y && apt-get install bash -y && apt-get install git openssh-server -y
WORKDIR /app
RUN npm install -g @angular/cli@^15.0.4 -y
RUN npm install
