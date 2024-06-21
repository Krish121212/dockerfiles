FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]

# RUN instruction will execute at the time of image creation --> docker build -t cmd:1.0 .
# CMD will run at the time of container creation i.e docker run -->  docker run -d -p 8081:80 cmd:1.0



# systemctl won't work in docker
