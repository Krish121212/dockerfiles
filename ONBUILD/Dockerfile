# I am the author of this image
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;"]

# Useful a trigger, if someone is trying to use your image, you can force them to add files/config's etc