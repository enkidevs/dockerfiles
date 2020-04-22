# AWS EB CLI Docker Image

[Docker image](https://hub.docker.com/r/enkici/awsebcli/) extending [Python](https://hub.docker.com/_/python) and installing [AWS EB CLI](https://github.com/aws/aws-elastic-beanstalk-cli).

- Building an image

```bash
docker build \
  --tag enkici/awsebcli \
  --build-arg PYTHON_VERSION="3.6-alpine" \
  --build-arg AWS_EB_CLI_VERSION="3.14.5" \
  .
```

- Tag the image

```bash
docker tag enkici/awsebcli enkici/awsebcli:3.14.5
```

- Push the image

```bash
docker push enkici/awsebcli:3.14.5
```
