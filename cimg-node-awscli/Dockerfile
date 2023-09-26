ARG NODE_VERSION=latest

FROM cimg/node:$NODE_VERSION


RUN sudo apt-get update
RUN sudo apt-get install -y python3 python3-pip python3-dev
RUN sudo pip3 install awscli
RUN sudo pip install "pyyaml<5.4"
RUN sudo pip install --upgrade setuptools
RUN sudo pip3 install awsebcli --upgrade


ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy