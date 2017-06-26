Docker Alpine PHP CLI Image
==================================================

A PHP CLI based on Alpine.

```
# Bash into the container and mount the current directory
$ docker run --rm -it -v$PWD:/app dannyben/alpine-php bash
```

If you are using the source repository, you can use the provided Runfile for 
some additional convenience commands.

```
$ gem install runfile
$ run --help
```

- [View on Docker Hub][1]
- [View on GitHub][2]

[1]: https://hub.docker.com/r/dannyben/alpine-php/
[2]: https://github.com/DannyBen/docker-alpine-php