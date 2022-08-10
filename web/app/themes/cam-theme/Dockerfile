FROM node:16-alpine

WORKDIR /theme

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 3000

CMD [ "yarn", "dev" ]
