FROM node:16-alpine

COPY . /app

WORKDIR /app

RUN yarn install

EXPOSE 80/tcp

CMD yarn start