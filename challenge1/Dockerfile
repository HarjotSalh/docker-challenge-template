# Use an official NGINX image as the base image
FROM nginx:alpine

# Copy the static content into the nginx directory
COPY public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Command to start nginx
CMD ["nginx", "-g", "daemon off;"]
