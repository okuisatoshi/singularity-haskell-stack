Bootstrap:docker
From: ubuntu:18.04

%post
apt-get update && \
apt-get install -y build-essential git curl wget &&\
apt-get clean
curl -sSL https://get.haskellstack.org/ | sh

%runscript
stack "$@"



