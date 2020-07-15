FROM node:alpine

RUN apk update

WORKDIR /app

COPY ./package.json ./

RUN npm update --save/--save-dev -f

RUN npm install
RUN npm install popper.js
RUN npm install typescript
RUN npm install jquery

RUN npm audit fix
COPY . .

CMD [ "npm", "run", "start" ]