FROM gitpod/workspace-full:latest

RUN curl -fsSL https://get.pulumi.com | sh -s -- --version 3.1.0 && \
    curl -L https://aka.ms/InstallAzureCli | bash

ENV PATH="${PATH}:/home/gitpod/.pulumi/bin"
