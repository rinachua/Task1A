FROM nginx:latest

# Copy index.html to working directory
COPY index.html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Define the command to start application
CMD ["nginx", "-g", "daemon off;"]
