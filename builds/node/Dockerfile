
FROM node:10.5.0-alpine
LABEL maintainer="Paolo D'Onorio De Meo <paolo@proofmedia.io>"

RUN apk --no-cache update && \
    apk --no-cache upgrade && apk add \
    bash less vim git \
    g++ make bash zlib-dev \
    python \
    && rm -rf /var/cache/apk/*
# NOTE: web3 js requires python2 to be installed
