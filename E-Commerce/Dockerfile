# Using a lightweight web server image
FROM nginx:alpine

# Remove default nginx configuration if you want to customize; optional
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy site content to nginx html directory
COPY ./E-Commerce/ /usr/share/nginx/html


# Expose HTTP port
EXPOSE 80

# Run nginx in foreground
CMD ["nginx", "-g", "daemon off;"]
