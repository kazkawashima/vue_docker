FROM node:9-alpine
RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh
RUN npm install -g vue-cli firebase-tools

WORKDIR /app

ENV HOST 0.0.0.0

EXPOSE 3000
