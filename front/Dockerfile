FROM node:16-alpine

COPY . /app

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

RUN yarn install
RUN yarn global add react-scripts

EXPOSE 80/tcp

CMD yarn start
