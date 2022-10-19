FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app

COPY package.json package.json
COPY package-lock.json package-lock.json
RUN npm i 

COPY src src 

CMD npm start