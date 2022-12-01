# LTS version (ubuntu), Jammy version (ubuntu-22.04), Focal version (ubuntu-20.04), Bionic version (ubuntu-18.04)
ARG UBUNTU_VERSION=ubuntu

FROM mcr.microsoft.com/devcontainers/base:${UBUNTU_VERSION}
RUN apt-get update && apt-get install -y \
    jq