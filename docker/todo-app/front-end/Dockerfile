FROM node:14-alpine

WORKDIR /front-end-app

EXPOSE 3000

ADD ./node_modules.tar.gz /front-end-app/

COPY . /front-end-app/

CMD [ "npm", "start"]
