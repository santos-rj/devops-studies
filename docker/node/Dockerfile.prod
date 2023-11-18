FROM node:20

WORKDIR /src/src/app

COPY . .

EXPOSE 3000

RUN npm ci

CMD ["node", "index.js"]