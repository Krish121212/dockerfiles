FROM nginx:alpine-slim
COPY nginx.conf /etc/nginx/nginx.conf
COPY ./my-app /usr/share/nginx/html
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]
# Nginx in the foreground, ensuring that the Docker container keeps running. The -g "daemon off;" 
# flag tells Nginx not to run as a background process (daemon), which is necessary for Docker containers to stay alive.
