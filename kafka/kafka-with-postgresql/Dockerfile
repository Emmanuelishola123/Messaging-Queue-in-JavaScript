FROM node:16.9.0-alpine
WORKDIR /kafka-with-postgresql
COPY package.json index.ts /kafka-with-postgresql/
RUN npm install
RUN npm i -g nodemon ts-node ts-node-dev
CMD [ "nodemon" "--exec", "ts-node", "index.ts" ]