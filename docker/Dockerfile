FROM mrcide/hiv-orderly:latest

RUN install_packages --repo="https://mrc-ide.r-universe.dev" \
    threemc

RUN install_remote mrc-ide/rrq@orderly1compat

WORKDIR /orderly
