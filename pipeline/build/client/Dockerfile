FROM node:14-alpine

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json package-lock.json ./
RUN npm install
COPY . .

CMD npm start
