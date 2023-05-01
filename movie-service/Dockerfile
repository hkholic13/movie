FROM node:16-alpine

WORKDIR /usr/src/app

COPY package.json ./
RUN npm install -g npm@latest
RUN npm install

COPY src src/

CMD ["sh", "-c", "npm start" ]