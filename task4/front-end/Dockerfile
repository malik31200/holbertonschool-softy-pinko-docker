FROM nginx:latest

# Copy the files from front end
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy config nginx
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf