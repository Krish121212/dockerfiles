FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]

# CMD will run at the time of container creation
# systemctl won't work in docker
