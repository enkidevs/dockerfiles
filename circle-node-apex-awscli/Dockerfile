ARG NODE_VERSION=latest

FROM enkici/circle-node-awscli:$NODE_VERSION

RUN sudo chown -R $(whoami) /usr/local/* && \
  sudo curl https://raw.githubusercontent.com/apex/apex/master/install.sh | sh

ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy
