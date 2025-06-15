# Use an Nginx base image to serve static files
FROM nginx:alpine

# Copy website files to Nginx's default directory
COPY . /usr/share/nginx/html

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
