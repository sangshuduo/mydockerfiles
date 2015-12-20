FROM ubuntu:14.04

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
    lib32bz2-1.0 \
    lib32ncurses5 \
    lib32stdc++6 \
    lib32z1 \
    libncurses5-dev \
    libncursesw5-dev \
    mercurial \
    texinfo \
    u-boot-tools \
    unzip \
    vim-nox \
    wget \
    zlib1g-dev \
    --no-install-recommends; \
    apt-get clean

