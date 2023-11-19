FROM node:20

WORKDIR /usr/src/app

RUN npm i -g @nestjs/cli

RUN nest new nestjs --package-manager npm

WORKDIR /usr/src/app/nestjs

ENTRYPOINT [ "npm", "run" , "start:dev"]