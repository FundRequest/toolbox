FROM debian:8.7
LABEL maintainer "karel@striegel.be"

RUN apt-get update && \
    apt-get upgrade && \
    apt-get install curl vim git -y && \
    curl -sL https://deb.nodesource.com/setup_7.x |  bash - && \
    apt-get install -y nodejs && \
    apt-get install -y build-essential && \
    npm install -g ethereumjs-testrpc && \
    node --version && \
    npm --version


EXPOSE 8545

ENTRYPOINT ["testrpc"]
