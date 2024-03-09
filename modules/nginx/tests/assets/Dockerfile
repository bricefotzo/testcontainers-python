# Use the official image as a parent image
FROM nginx:alpine

# Delete the default Nginx configuration file
RUN rm /etc/nginx/conf.d/default.conf

# Copy a custom Nginx configuration file from your host to your image
COPY nginx.conf /etc/nginx/conf.d/

# Copy a custom index.html file from your host to your image
COPY index.html /usr/share/nginx/html/

# Expose port 8080
EXPOSE 8080
