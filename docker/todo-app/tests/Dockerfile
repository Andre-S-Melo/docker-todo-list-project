FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests-app

ADD ./node_modules.tar.gz /tests-app/

COPY . /tests-app/

CMD [ "npm", "test"]
