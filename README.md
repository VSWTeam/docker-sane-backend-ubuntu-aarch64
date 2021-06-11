# SANE Backend build environment (Ubuntu - AARCH64) Dockerfile

## Base Docker Image

* [arm64v8/ubuntu:18.04](https://hub.docker.com/r/arm64v8/ubuntu/)

## Build

```bash
docker build --rm -t "vswteam/sane-backend-ubuntu-aarch64" .
```

## Download

```bash
docker pull vswteam/sane-backend-ubuntu-aarch64
```

### Usage

```bash
docker run -it -v <sane-backend-volume>:/root/project vswteam/sane-backend-ubuntu-aarch64 /bin/bash
```
