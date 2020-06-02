FROM docker:19.03

RUN apk add curl jq
RUN mkdir -p ~/.docker/cli-plugins
RUN curl -fsSL -o ~/.docker/cli-plugins/docker-buildx "https://github.com/docker/buildx/releases/download/v${DOCKER_BUILDX_VERSION}/buildx-v${DOCKER_BUILDX_VERSION}.linux-amd64"
RUN chmod +x ~/.docker/cli-plugins/docker-buildx