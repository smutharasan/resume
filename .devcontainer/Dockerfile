FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Remove unsigned Yarn repo BEFORE features run
RUN rm -f /etc/apt/sources.list.d/yarn.list \
    && apt-get update
