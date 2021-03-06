# Circle Node Apex AWS CLI Image

[Docker image](https://hub.docker.com/r/enkici/circle-node-apex-awscli) extending [CircleCI Node Image](https://hub.docker.com/r/circleci/node/) and installing [Apex](http://apex.run) and [AWS CLI](https://github.com/aws/aws-cli).


- Building an image

```bash
docker build \
  --tag enkici/circle-node-apex-awscli \
  --build-arg NODE_VERSION="8.10.0" \
  --label "CircleCI Node 8.10.0 with Apex and AWS CLI" \
  .
```

- Tag the image with proper version tag

```bash
docker tag enkici/circle-node-apex-awscli enkici/circle-node-apex-awscli:8.10.0
```

- Push the image to Dockerhub

```bash
docker push enkici/circle-node-apex-awscli:8.10.0
```
