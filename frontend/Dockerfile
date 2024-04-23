# Stage 1: Build the application using Node.js
FROM node:latest as build
WORKDIR /app
COPY . /app
RUN npm install
WORKDIR /app/frontend/src
CMD ["npm" ,"run","start"]