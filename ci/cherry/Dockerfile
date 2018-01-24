FROM mohuk/ci:aws

RUN apk add --no-cache \
		curl \
		openssl \
		ca-certificates

RUN apk add xmlstarlet bash --update --repository http://dl-4.alpinelinux.org/alpine/edge/testing \
	&& rm -rf /var/cache/apk/*

