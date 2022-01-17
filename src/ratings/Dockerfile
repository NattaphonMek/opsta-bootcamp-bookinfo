FROM node:16.8.0-alpine3.12

WORKDIR /usr/src/app/

COPY ratings.js /usr/src/app/
COPY package.json /usr/src/app/

RUN npm install

EXPOSE 8080

CMD ["node", "/usr/src/app/ratings.js", "8080"]