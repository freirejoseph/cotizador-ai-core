FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    git curl wget unzip zip python3 python3-pip python3-venv \
    build-essential ca-certificates nano iputils-ping \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
