FROM mohuk/ci

ENV VERSION 1.14.25

RUN apk --no-cache add python3 && \
	pip3 install --upgrade pip setuptools && \
	pip3 --no-cache-dir install awscli==${VERSION} && \
	rm -rf /var/cache/apk/*
