FROM nginx:latest

ENV HOST 0.0.0.0

COPY dist /usr/share/nginx/html
COPY ci/nginx/default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

