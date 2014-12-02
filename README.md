docker-redis3-rc
================

Dockefile to build (from source) latest release candidate of redis version three.

Build from source redis3 v3 release candidate dockerfile.

allows you to play with new redis clustering functionality in a docker container


# Build / Pull Image Instructions

- `git clone https://github.com/rednut/docker-redis3-rc.git`
- `cd docker-redis3-rc`
- `docker build -t="rednut/redis3" .`

or to pull/fetch a pre-built image:

- `docker pull rednut/docker-redis3-rc:latest`


# running the redis3 container

`docker run -i -t --rm rednut/docker-redis3-rc:latest`

the usual redis port `6379` has been "exposed" to allow linking containers


