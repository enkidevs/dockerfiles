ARG NODE_VERSION=latest

FROM cimg/node:$NODE_VERSION

RUN sudo apt-get update && \
  sudo apt-get install -y python3 python-pip3 python-dev && \
  sudo pip3 install awscli && \
  sudo pip3 install awsebcli --upgrade && \
  sudo apt-get clean

ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy
