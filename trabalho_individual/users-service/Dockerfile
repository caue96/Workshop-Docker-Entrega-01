FROM node:14.17.5

WORKDIR /app/chat-app

COPY package.json yarn.lock ./

RUN yarn

COPY . .

EXPOSE 7101

CMD yarn db:migrate && yarn watch