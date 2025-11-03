FROM mcr.microsoft.com/devcontainers/dotnet
LABEL maintainer="dierod3143 <diego.rodriguez3143@ctag.com>"

RUN mkdir /opt/actions-runner && \
  cd /opt/actions-runner && \
  curl -o actions-runner-linux-x64-2.329.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.329.0/actions-runner-linux-x64-2.329.0.tar.gz && \
  tar xzf ./actions-runner-linux-x64-2.329.0.tar.gz && \
  rm ./actions-runner-linux-x64-2.329.0.tar.gz && \
  chmod -R 777 .
