FROM node:12
EXPOSE 8080
RUN mkdir -p /bindmount
WORKDIR /bindmount
COPY package.json  webpack.config.js ./
RUN yarn install && yarn run build
CMD yarn start:frontend