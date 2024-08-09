FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]

# RUN instruction will execute during the build process of the docker image
                # used to install packages etc --> docker build -t cmd:1.0 .
# We can have multiple RUN in dockerfile.

# CMD specifies the default command to run when a container is started from the Docker image 
                # -->  docker run -d -p 8081:80 cmd:1.0
# Only one CMD per docker file. if multiple then last one will be taken to consideration.



# systemctl won't work in docker
