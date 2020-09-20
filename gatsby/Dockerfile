FROM node:14.11.0

RUN npm install -g gatsby-cli

WORKDIR /app

COPY package*.json ./
RUN npm install

RUN ls

COPY . .

RUN ls node_modules/

EXPOSE 8000
CMD ["gatsby", "develop"]
