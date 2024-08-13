# build stage
FROM node:lts-alpine AS build-production

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8081

CMD ["npm", "run", "start"]