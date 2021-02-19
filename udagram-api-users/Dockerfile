FROM node:13

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 8081

CMD ["npm", "run", "prod"]