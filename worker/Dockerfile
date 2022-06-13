FROM node:14-alpine

WORKDIR /worker

COPY ./package*.json ./

RUN npm install

COPY ./ ./

CMD [ "npm" , "run" , "start" ]
