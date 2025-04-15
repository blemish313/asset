FROM ubuntu:24.04

# Prevent interactive prompts during install
ENV DEBIAN_FRONTEND=noninteractive

# Install basic tools
RUN apt update && apt install -y \
    curl \
    git \
    python3 \
    python3-pip \
    build-essential

# Add this line so the SSH feature works properly with non-root
ARG USERNAME=vscode
