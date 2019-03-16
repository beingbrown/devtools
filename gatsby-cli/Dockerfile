FROM node:10.15.1-alpine

RUN apk update && apk add git git-perl

RUN npm install gatsby-cli -g

RUN mkdir -p /gatsby/app
WORKDIR /gatsby/app

ENTRYPOINT ["gatsby"]
