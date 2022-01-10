FROM node:14.12-alpine

WORKDIR /app

COPY . /app
RUN npm build

ENTRYPOINT ["npm", "run", "serve"]