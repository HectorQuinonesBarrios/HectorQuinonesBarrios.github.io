FROM node:alpine

ADD . /usr/src/app

WORKDIR /usr/src/app

RUN npm i docsify-cli -g

EXPOSE 3000

CMD docsify serve .
