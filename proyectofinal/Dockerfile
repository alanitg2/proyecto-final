FROM node:18 as build
COPY package.json package-lock.json ./
RUN npm install
COPY . .
RUN npm run build --prod
