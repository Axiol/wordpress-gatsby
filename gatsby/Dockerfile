FROM node:14.11.0

WORKDIR /app

RUN npm install -g gatsby-cli

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000
CMD ["gatsby", "develop", "-H", "0.0.0.0"]
