FROM node:18.1.0-alpine3.14

WORKDIR /app

COPY package.json ./
COPY yarn.lock ./

COPY ./ ./

RUN yarn

CMD ["yarn", "start"]
