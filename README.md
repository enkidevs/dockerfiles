# 🐳 Enki Dockerfiles

This repo contains some deprecated Docker files:

- circle-node-apex
- circle-node-apex-awscli
- awseblci
- circle-node-awscli

These Images need manual deployment. See individual folders for more info.

The `cimg-node-awscli` image is set-up with automatic deployments.

A deployment is triggered if the `Dockerfile` or `variables.json` file within its folder contain any changes when pushing to `master`.

The `variables.json` file contains any dynamic arguments used for the build/push process, namely:

- NODE_VERSION
- TAG (on DockerHub)

These are read by the CI pipeline which will build, tag and push the image to its repo on DockerHub.