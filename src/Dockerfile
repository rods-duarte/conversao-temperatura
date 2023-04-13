FROM node:19.0.2
WORKDIR /usr/app/
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]