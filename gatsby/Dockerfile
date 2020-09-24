FROM node:14.11.0

RUN npm install -g gatsby-cli

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000
CMD ["gatsby", "develop", "-H", "0.0.0.0"]
