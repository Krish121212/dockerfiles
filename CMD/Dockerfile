FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]

# CMD will run at the time of container creation  -->  docker run -d -p 8081:80 cmd:1.0
# RUN instruction will execute at the time of image creation --> docker build -t cmd:1.0 .


# systemctl won't work in docker
