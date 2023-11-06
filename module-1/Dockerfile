# Use the official Nginx base image
FROM nginx:latest

# Copy your HTML file into the container
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 for web traffic
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
