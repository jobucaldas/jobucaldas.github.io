FROM node:20-bullseye-slim

RUN npm install -g bun

WORKDIR /usr/src/app

COPY package*.json ./

RUN bun install

EXPOSE 3000

COPY . .

CMD bun run dev
