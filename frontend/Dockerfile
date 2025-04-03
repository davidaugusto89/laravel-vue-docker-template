FROM node:23-alpine

RUN apk add --no-cache bash

WORKDIR /app

COPY . .

RUN npm install -g @quasar/cli

RUN npm install

EXPOSE 9000

CMD ["quasar", "dev", "--hostname", "0.0.0.0"]