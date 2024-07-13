FROM node:20 as build
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080
CMD [ "npm", "start"]