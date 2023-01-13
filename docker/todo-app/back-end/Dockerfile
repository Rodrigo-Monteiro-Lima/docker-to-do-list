FROM node:14-alpine

# WORKDIR /usr/src/app/back-end

COPY package*.json ./

EXPOSE 3001

ADD node_modules.tar.gz ./

COPY ./ ./

# RUN npm start

ENTRYPOINT [ "npm", "start" ]
