# Gunakan Ubuntu 22.04 sebagai base image
FROM ubuntu:22.04

# Non-interaktif biar nggak nunggu input waktu install
ENV DEBIAN_FRONTEND=noninteractive

# Install Docker CLI (bukan Docker daemon)
RUN apt-get update && \
    apt-get install -y \
    docker.io \
    curl \
    git \
    sudo \
    vim \
    iproute2 \
    iputils-ping && \
    apt-get clean
