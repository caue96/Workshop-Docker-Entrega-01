FROM node:14.17.5

WORKDIR /app/api-gateway

COPY package.json yarn.lock ./

RUN yarn

COPY . .

EXPOSE 7000

CMD ["yarn", "watch"]