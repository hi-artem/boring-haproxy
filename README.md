# boring-haproxy

Docker images of Haproxy 2.3 with BoringSSL version of OpenSSL.

Versions based on Ubuntu Xenial, Bionic and Focal

## Running the container

```sh
docker run --init -d --rm  aakatev/boring-haproxy:bionic
```

## Building the image yourself

```sh
docker build --build-arg UBUNTU_RELEASE=xenial/bionic/focal -t boring-haproxy .
```
