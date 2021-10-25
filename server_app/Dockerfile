FROM node:12
RUN mkdir -p /usr/src/server_app
EXPOSE 3000
WORKDIR /usr/src/server_app
COPY  package.json /usr/src/server_app
RUN yarn install
COPY . /usr/src/server_app
CMD yarn start:dev