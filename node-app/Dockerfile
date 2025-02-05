FROM node:14

WORKDIR /usr/src/app

LABEL org.opencontainers.image.source=https://github.com/testwl12/actionstest
LABEL org.opencontainers.image.description="My container image"
LABEL org.opencontainers.image.licenses=MIT

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]