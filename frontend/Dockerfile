FROM node:alpine 

WORKDIR /app

COPY . .

RUN yarn install

COPY . .

RUN yarn build

CMD ["yarn", "start"]