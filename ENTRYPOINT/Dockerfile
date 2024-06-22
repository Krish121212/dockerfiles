FROM almalinux:9
CMD [ "google.com" ]
ENTRYPOINT [ "ping","-c5" ]

# CMD instruction can be overriden from runtime
# entrypoint instrection can't be overriden but it will apend the info which we gave in runtime

# But we can mix CMD and entrypoint for better results, CMD supplies default arguments to entrypoint
# We can always override default args from cmd at runtime