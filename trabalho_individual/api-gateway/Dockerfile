FROM graphql:15.5.1

WORKDIR /app/api-gateway

COPY package.json /app/api-gateway/package.json

RUN yarn

EXPOSE 7000

CMD ["yarn", "watch"]