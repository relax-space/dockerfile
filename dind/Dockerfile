FROM docker:19.03.1-dind
MAINTAINER xiao.xinmiao <xiaoxm_001@outlook.com>

RUN apk add --no-cache py-pip python-dev libffi-dev openssl-dev gcc libc-dev make bash
RUN pip install docker-compose

ENTRYPOINT ["/bin/bash", "-c"]