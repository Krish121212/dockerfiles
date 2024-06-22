FROM almalinux:9
RUN adduser Krishna
USER Krishna
CMD ["sleep","100"]

# we should not allow containers to run with root access
# If you are not adding user in your image, containers runs with access ROOT. SO need to add above always