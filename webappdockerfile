# Use the official Apache HTTPD image as a base
FROM httpd:alpine

# Copy the index.html into the Apache server's default directory
COPY index.html /usr/local/apache2/htdocs/index.html

# Expose port 80 for the HTTP server
EXPOSE 80

# Apache HTTP server runs by default, so no need for CMD
