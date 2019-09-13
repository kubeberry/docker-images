ARG VERSION=latest
FROM kubeberry/python2:$VERSION

RUN apk --no-cache add \
    gcc libffi-dev musl-dev openssl-dev \
    python2-dev py2-pip

RUN pip install ansible
