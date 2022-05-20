# https://docs.docker.com/develop/develop-images/dockerfile_best-practices/

# to build it use:
# docker build -t xin-vim .

FROM alpine:latest

RUN apk update \
	&& apk upgrade \
	&& apk add vim

ENTRYPOINT [ "vim" ]
