FROM node:10.15.1-alpine

RUN npm install express-generator -g

RUN mkdir -p /express/app
WORKDIR /express/app

ENTRYPOINT ["express"]
