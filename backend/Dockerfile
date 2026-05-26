FROM node:24-alpine

WORKDIR /app

ENV NODE_ENV=development 

COPY package*.json .
COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]