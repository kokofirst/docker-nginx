FROM nginx:stable-alpine

RUN addgroup -g 2200 -S www-data && adduser -D -S -h /var/cache/www-data -s /sbin/nologin -G www-data -u 2200 www-data && chown -R www-data:www-data /var/cache/nginx

WORKDIR /data/wwwroot