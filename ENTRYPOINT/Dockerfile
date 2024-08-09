FROM almalinux:9
CMD [ "google.com" ]
ENTRYPOINT [ "ping","-c5" ]

# CMD instruction can be overriden from runtime
# entrypoint instrection can't be overriden but it will apend the info which we gave in runtime

# But we can mix CMD and entrypoint for better results, CMD supplies default arguments to entrypoint
# We can always override default args from cmd at runtime

# Another ex
FROM ubuntu:20.04
ENTRYPOINT ["echo"]
CMD ["Hello World"]

# Output: Hello World


# Another Ex
FROM ubuntu:20.04
ENTRYPOINT ["Hello"]
CMD ["Hello"]

#Output: Hello Hello

# Another Ex
FROM ubuntu:20.04
ENTRYPOINT ["Hello"]
CMD ["Hello"]

# docker run image_name world
# Output: Hello world

# CMD: Use when you want a default command but allow users to override it easily.
# ENTRYPOINT: Use when you want to enforce a command that should always run, with optional arguments.


