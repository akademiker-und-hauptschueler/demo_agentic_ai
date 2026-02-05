FROM mcr.microsoft.com/devcontainers/typescript-node:20

# Avoid interactive prompts in any additional installs
ENV DEBIAN_FRONTEND=noninteractive

# Install only extra system dependencies we actually need
RUN apt-get update && apt-get install -y \
    fonts-dejavu \
    fonts-liberation \
    firefox-esr \
    && rm -rf /var/lib/apt/lists/*

# Quick sanity check – Node is already provided by the base image
RUN node --version && npm --version