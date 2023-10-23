FROM node:18.18.2

WORKDIR /app

RUN yarn install

COPY . .

EXPOSE 3000

CMD ["yarn", "dev"]