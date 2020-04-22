ARG PYTHON_VERSION=

FROM python:${PYTHON_VERSION}

ARG AWS_EB_CLI_VERSION=

RUN apk update
RUN apk add --no-cache --virtual .build-deps
RUN apk add bash
RUN apk add make && apk add curl && apk add openssh
RUN apk add git
RUN echo "Installing awsebcli ${AWS_EB_CLI_VERSION}"
RUN pip install awsebcli==${AWS_EB_CLI_VERSION}
