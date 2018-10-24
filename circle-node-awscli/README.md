# Circle Node AWS Cli Docker Image

[Docker image](https://hub.docker.com/r/enkici/circle-node-awscli/) extending [CircleCI Node Image](https://hub.docker.com/r/circleci/node/) and installing [AWS CLI](https://github.com/aws/aws-cli).

- Building an image

```bash
docker build \
  -t enkici/circle-node-awscli \
  --build-arg NODE_VERSION="8.10.0" \
  --label "CircleCI Node 8.10.0 with AWS cli" \
  .
```
