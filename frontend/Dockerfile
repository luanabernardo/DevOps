# Dockerfile for React app
FROM node:14

WORKDIR /script.js

COPY package.json ./

RUN npm install

COPY . ./

EXPOSE 3000

CMD ["npm", "start"]