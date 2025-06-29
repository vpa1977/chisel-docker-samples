# Installing a Custom Certificate in a Chiseled JRE

This repository provides sample Dockerfiles demonstrating how to install a custom root CA certificate into an [Ubuntu Chiseled](https://www.google.com/search?q=https://canonical.com/blog/ubuntu-chiseled) Java Runtime Environment (JRE) container.

## How to Build the Samples

To build the sample images, run the following [docker build](https://www.google.com/search?q=httpss://docs.docker.com/engine/reference/commandline/build/) commands from your terminal:

### For the chiselled JRE 8

```bash
docker build -t custom-certificate-8 . -f Dockerfile.8_edge
```

### For the chiselled JRE 21

```bash
docker build -t custom-certificate-21 . -f Dockerfile.21_edge
```
