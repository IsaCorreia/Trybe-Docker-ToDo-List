FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /tests
COPY package*.json ./
ADD node_modules.tar.gz ./
RUN npm install
COPY . .