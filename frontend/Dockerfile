FROM node:20-alpine

WORKDIR /app

COPY frontend/package.json frontend/package-lock.json ./
COPY config /config
RUN npm install

COPY frontend /app

CMD npm run dev