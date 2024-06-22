ARG version
FROM almalinux:${version:-8}
ARG Name
ARG Tool
RUN echo "This is ${Name}, practicing ${Tool}"
CMD [ "sleep","100" ]

# ARG can be first instruction in only one case - before from to get version
# 2nd line :-8 if user gives any version it takes otherwise default version 8 will be installed
