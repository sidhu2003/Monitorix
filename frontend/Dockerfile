FROM node:14.17.0-alpine

WORKDIR /app
EXPOSE 3000

COPY package.json ./
RUN npm install

COPY . .

CMD ["npm", "start"]