FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/app/tests

COPY package*.json ./

ADD node_modules.tar.gz ./

COPY ./ ./

ENTRYPOINT [ "npm", "test" ]