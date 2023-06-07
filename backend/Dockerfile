FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=victor
ENV MONGODB_PASSWORD=secret

CMD [ "npm", "start" ]