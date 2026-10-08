FROM mcr.microsoft.com/devcontainers/rust:2-1-trixie@sha256:7ea67e836ab768910de3810355ae0a0b06d63c14f2159708b6e5758c01532bf7

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get --yes install --no-install-recommends mold
