# Use an official Nginx image to serve the Angular app
FROM nginx:alpine

# Copy the Angular build output to the Nginx server
COPY dist/angularapp /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
