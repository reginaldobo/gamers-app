FROM node:slim

RUN mkdir /app
WORKDIR /app

RUN cd /app
COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node","./dist/bin/app.js"]


