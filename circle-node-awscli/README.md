# Circle Node AWS Cli Docker Image

[Docker image](https://hub.docker.com/r/enkici/circle-node-awscli/) extending [CircleCI Node Image](https://hub.docker.com/r/circleci/node/) and installing [AWS CLI](https://github.com/aws/aws-cli).

- Building an image

```bash
docker build \
  -t enkici/circle-node-awscli \
  --build-arg NODE_VERSION="12.14.1"
  .
```

- Tag the image

```bash
docker tag enkici/circle-node-awscli enkici/circle-node-awscli:12.14.1
```

- Push the image

```bash
docker push enkici/circle-node-awscli:12.14.1
```
