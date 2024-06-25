# Use the official Nginx image from the Docker Hub
FROM nginx:latest


# Copy custom Nginx configuration file
COPY ./reverse-proxy/nginx.conf /etc/nginx/nginx.conf
COPY ./reverse-proxy/certs/mechkeys.ddns.net.crt /etc/nginx/certs/mechkeys.ddns.net.crt

# Copy HTML files to the Nginx web root directory
#COPY ./html /var/www/html

# Start PHP-FPM in the background and Nginx in the foreground
#CMD php-fpm && nginx -g 'daemon off;'

