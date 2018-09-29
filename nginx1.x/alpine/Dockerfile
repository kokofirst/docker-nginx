FROM nginx:1.15.4-alpine

RUN groupadd -g 2200 -r www-data && useradd -r -g www-data -u 2200 -s /sbin/nologin www-data && chown -R www-data:www-data /var/cache/nginx

WORKDIR /data/wwwroot