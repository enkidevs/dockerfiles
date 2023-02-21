# Circle Node AWS CLI Docker Image

[Docker image](https://hub.docker.com/r/enkici/cimg-node-awscli) extending [CircleCI Node Image](https://hub.docker.com/r/cimg/node/) and installing [AWS CLI](https://github.com/aws/aws-cli).

- Building an image

```bash
docker build \
  --tag enkici/cimg-node-awscli \
  --build-arg NODE_VERSION="16.17.0"
  .
```

- Tag the image

```bash
docker tag enkici/cimg-node-awscli enkici/cimg-node-awscli:16.17.0
```

- Push the image

```bash
docker push enkici/cimg-node-awscli:16.17.0
```
