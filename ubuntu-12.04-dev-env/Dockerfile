FROM ubuntu:12.04

# Packaged dependencies
RUN     apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -yq \
    automake \
    bc \
    bison \
    build-essential \
    ca-certificates \
    curl \
    device-tree-compiler \
    fakeroot \
    flex \
    gettext \
    git \
    ia32-libs \
    libncurses5-dev \
    libncursesw5-dev \
    mercurial \
    texinfo \
    u-boot-tools \
    uboot-mkimage \
    unzip \
    vim-nox \
    wget \
    zlib1g-dev \
    --no-install-recommends; \
    apt-get clean

