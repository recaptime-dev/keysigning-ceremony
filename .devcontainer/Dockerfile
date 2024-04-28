FROM gitpod/workspace-full:latest

# install our essientials
RUN brew update && brew upgrade && brew install shellcheck hadolint keychain dopplerhq/cli/doppler

RUN wget https://prerelease.keybase.io/keybase_amd64.deb -O /tmp/keybase_amd64.deb \
    && sudo install-packages /tmp/keybase_amd64.deb --fix-missing
