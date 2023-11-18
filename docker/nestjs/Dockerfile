FROM node:20

WORKDIR /app

RUN npm i -g @nestjs/cli

RUN nest new nestjs --package-manager npm

WORKDIR /app/nestjs

ENTRYPOINT [ "npm", "run" , "start:dev"]