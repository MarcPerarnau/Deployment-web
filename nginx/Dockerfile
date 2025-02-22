FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf

COPY php /var/www/html


RUN chown -R www-data:www-data /var/www/html

EXPOSE 80
