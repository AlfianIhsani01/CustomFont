FROM alpine:latest

# Install required packages
RUN apk update && apk add --no-cache \
    build-base \
    curl \
    git \
    neovim \
    which \
    tmux \
    openssh \
    zsh \
    shadow \
    sudo \
    && rm -rf /var/cache/apk/*
