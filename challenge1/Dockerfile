# Use the official NGINX image from Docker Hub
FROM nginx:alpine

# Copy the contents of the public folder to the NGINX html directory
COPY public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]

# This was sourced from ChatGPT
# [1] ChatGPT, "Creating a Dockerfile to Serve Static Content with NGINX," Unpublished, 2024.
