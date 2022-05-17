FROM node:14-alpine

WORKDIR /back-end-app

EXPOSE 3001

ADD ./node_modules.tar.gz /back-end-app/

COPY . /back-end-app/

CMD [ "npm", "start"]
