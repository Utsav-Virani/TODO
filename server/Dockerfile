FROM node:latest

WORKDIR /usr/src/todo

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm","start"]