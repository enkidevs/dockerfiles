# Circle Node AWS CLI Docker Image

[Docker image](https://hub.docker.com/r/enkici/postgres-pg-similarity/) extending [CircleCI Node Image](https://hub.docker.com/r/circleci/node/) and installing [AWS CLI](https://github.com/aws/aws-cli).

- Building an image

```bash
docker build \
  --tag enkici/postgres-pg-similarity \
  --build-arg PG_VERSION="11.19-alpine" \
  .
```

- Tag the image

```bash
docker tag enkici/postgres-pg-similarity enkici/postgres-pg-similarity:11.19-alpine
```

- Push the image

```bash
docker push enkici/postgres-pg-similarity:11.19-alpine
```
