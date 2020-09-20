FROM node:14.11.0-alpine

RUN npm install -g gatsby-cli

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8000
CMD ["gatsby", "develop"]
