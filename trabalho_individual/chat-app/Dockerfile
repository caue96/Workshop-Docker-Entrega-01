FROM node:14.17.5

WORKDIR /app/chat-app

COPY package.json yarn.lock ./

RUN yarn

COPY . .

EXPOSE 7001

CMD ["yarn", "watch"]