FROM node:13

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm i

COPY www .

EXPOSE 8080

CMD ["node", "server.js"]