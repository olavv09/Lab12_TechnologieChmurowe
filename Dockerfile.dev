FROM node:21.6.0-alpine3.19

WORKDIR '/app'
ENV NODE_OPTIONS=--openssl-legacy-provider
COPY package.json .
RUN npm install

COPY . .

CMD ["npm", "run", "start"]
