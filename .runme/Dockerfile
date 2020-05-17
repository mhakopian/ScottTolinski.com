FROM node:latest
WORKDIR /app
COPY . .
RUN npm run build
ENTRYPOINT npm install --global gatsby && npm run start
