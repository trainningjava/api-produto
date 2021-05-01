FROM node:14.16.1-alpine3.13
LABEL version="1.0"
LABEL description="Kubernetes Bootcamp Desafio2"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "app.js" ]
