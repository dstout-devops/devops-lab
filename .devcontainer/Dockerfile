FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get update -y \
    && apt-get dist-upgrade -y

# install k3d
# RUN curl -s https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash

# install k9s
# RUN wget https://github.com/derailed/k9s/releases/download/v0.32.5/k9s_linux_amd64.deb && apt install ./k9s_linux_amd64.deb && rm k9s_linux_amd64.deb

USER vscode