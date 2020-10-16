FROM cimg/node:12.19.0

RUN sudo apt-get update && \
  sudo apt-get install -y python3 python3-pip python-dev && \
  sudo pip3 install awscli && \
  sudo pip3 install awsebcli --upgrade && \
  sudo apt-get clean

ENV AWS_ACCESS_KEY_ID=dummy
ENV AWS_SECRET_ACCESS_KEY=dummy
ENV AWS_REGION=dummy
