FROM mcr.microsoft.com/devcontainers/php:1-8.2

RUN apt-get update && apt-get install -y \
    mysql-client \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace