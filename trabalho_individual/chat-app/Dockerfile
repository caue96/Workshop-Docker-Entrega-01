FROM node:14.17.5

WORKDIR /app/chat-app

COPY package.json /app/chat-app/package.json

RUN yarn

EXPOSE 7001

CMD ["yarn", "watch"]