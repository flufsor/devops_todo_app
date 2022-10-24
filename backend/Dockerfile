FROM node:17-alpine3.14

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

CMD ["node", "index.js"]

EXPOSE 3000
