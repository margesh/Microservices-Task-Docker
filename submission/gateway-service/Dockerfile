FROM node:18-alpine

WORKDIR /app

COPY ../../Microservices/gateway-service/package*.json ./
RUN npm install

COPY ../../Microservices/gateway-service .

EXPOSE 3003

CMD ["node", "app.js"]