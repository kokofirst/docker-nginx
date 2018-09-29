FROM nginx:1.15.4-alpine

RUN usermod -u 2200 www-data && groupmod -g 2200 www-data && chown -R www-data:www-data /var/cache/nginx

WORKDIR /data/wwwroot