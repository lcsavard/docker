FROM nginx:latest
COPY nginx.conf /etc/nginx/conf.d/default.conf
RUN apt update && apt install -y certbot python-certbot-nginx
