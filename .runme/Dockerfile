FROM bitnami/nginx:latest
WORKDIR /app
COPY public /usr/share/nginx/html
RUN npm run build
ENTRYPOINT ls
