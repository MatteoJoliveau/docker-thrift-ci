# Thrift Docker Images

This is a set of custom Docker images for using [Apache Thrift](https://thrift.apache.org) in Docker, especially
for usage inside Docker-based CI environment to build Thrift definitions during pipeline executions.

## Content
- `thrift-ci`: the base image with prebuilt `thrift` executable
- `java-thrift`: for building Java applications that use Thrift

All images are available on [Docker Hub](https://hub.docker.com/r/matteojoliveau)