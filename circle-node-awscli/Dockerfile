ARG NODE_VERSION=latest

FROM circleci/node:$NODE_VERSION

RUN sudo apt-get update && \
  sudo apt-get install -y python python-pip python-dev && \
  sudo pip install awscli && \
  sudo apt-get clean

ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy
