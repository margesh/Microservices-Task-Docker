FROM node:18-alpine

WORKDIR /app

COPY ../../Microservices/user-service/package*.json ./
RUN npm install

COPY ../../Microservices/user-service .

EXPOSE 3000

CMD ["node", "app.js"]