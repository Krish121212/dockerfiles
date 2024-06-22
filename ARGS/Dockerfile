ARG version
FROM almalinux:${version:-8}
ARG Name=Krishna
ARG Tool=Docker
ENV instrection=arg
RUN echo "This is ${Name}, practicing ${Tool}, and it's topic ${instrection}"
CMD [ "sleep","100" ]

# ARG can be first instruction in only one case - before from to get version
# 2nd line :-8 if user gives any version it takes(override)  otherwise default version 8 will be installed
# args in dockerfile, you can suply them through command line using "--build-arg Name=Krishna" in build statement before '.'
