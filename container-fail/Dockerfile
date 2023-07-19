FROM ubuntu:16.04
COPY secret.yaml /secret.yaml
RUN mkdir -p /home/se/.aws/
COPY awssecret.json /home/se/.aws/credentials
