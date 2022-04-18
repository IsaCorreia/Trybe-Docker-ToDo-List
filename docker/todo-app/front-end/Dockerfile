FROM node:14-alpine AS build
WORKDIR /front-end
COPY package*.json ./
ADD node_modules.tar.gz ./
RUN npm install
# RUN cat 'node_modules' > .dockerignore
COPY . .
# RUN npm start
EXPOSE 3000