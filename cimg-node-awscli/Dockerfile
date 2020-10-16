FROM cimg/node:12.19.0

RUN sudo apt-get update && \
  sudo apt-get install -y python python-pip python-dev && \
  sudo pip install awscli && \
  sudo pip install awsebcli --upgrade && \
  sudo apt-get clean

ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy
