FROM gitpod/workspace-full:latest

RUN curl -fsSL https://get.pulumi.com | sh -s -- --version 3.16.0 && \
    curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

ENV PATH="${PATH}:/home/gitpod/.pulumi/bin"
