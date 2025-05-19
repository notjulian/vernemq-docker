# docker-vernemq

This is a custom build of docker-vernemq, derived from the docker builds. Since version 1.10, vernemq requires payment for commercial use of their builds while custom builds can still be released unter Apache2 license.

This custom build allows to use newer versions of vernemq under Apache2 license.

Latest build available here: https://github.com/notjulian/vernemq-docker/pkgs/container/vernemq-docker

Run docker local (not for production!)
docker run -p 1883:1883 -e "DOCKER_VERNEMQ_ALLOW_ANONYMOUS=on" --name vernemq1 -d ghcr.io/notjulian/vernemq-docker:master
