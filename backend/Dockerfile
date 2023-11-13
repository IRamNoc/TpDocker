FROM node:10-alpine

WORKDIR /app

COPY package*.json ./

COPY . .

EXPOSE 3000

CMD npm install && npm start