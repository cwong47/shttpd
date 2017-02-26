# shttpd
This is a super basic http server that simulates a coin toss.
It is essentially a simple webapp which I use for testing Consul checks.

## Docker Hub
You can pull this image from my [docker hub](https://hub.docker.com/r/cwong47/shttpd/).
```
$ docker pull cwong47/shttpd
```

## Build
```
$ docker build -t cwong47/shttpd .
```

## Run
```
$ docker run -d -p 8080:8080 cwong47/shttpd
$ curl localhost:8080
head
```

# License and Authors
Authors: Calvin Wong

# Repo Location

[https://gitlab.com/cwong47/shttpd](https://gitlab.com/cwong47/shttpd.git)
