FROM node:14-alpine

RUN mkdir /front-app
WORKDIR /front-app

COPY . .

RUN npm install

CMD ["npm", "start"]

EXPOSE 3000
