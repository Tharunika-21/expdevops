FROM node:latest

WORKDIR /app

COPY .env /app/.env

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]


