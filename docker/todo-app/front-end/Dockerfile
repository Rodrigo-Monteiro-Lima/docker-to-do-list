FROM node:14-alpine

WORKDIR /usr/src/app/front-end

COPY package*.json ./

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY ./ ./

ENTRYPOINT [ "npm", "start" ]
