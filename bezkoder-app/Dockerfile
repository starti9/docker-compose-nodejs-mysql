FROM node:16

WORKDIR /docker-app
COPY package.json .
RUN npm install -g npm@9.4.2
COPY . .
CMD npm start
