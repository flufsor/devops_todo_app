FROM node:16-alpine3.16

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

CMD ["node", "index.js"]

EXPOSE 3000
