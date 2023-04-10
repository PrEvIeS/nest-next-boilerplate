FROM node:alpine
WORKDIR /usr/src/api
COPY package.json .
COPY yarn.lock .
RUN yarn install
COPY ./ ./

CMD ["yarn", "start:dev"]