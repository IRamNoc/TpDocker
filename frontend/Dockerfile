FROM node:14-alpine

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package*.json ./

COPY . .

EXPOSE 3001

CMD npm install && npm start