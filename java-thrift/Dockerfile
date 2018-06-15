FROM matteojoliveau/thrift-ci

LABEL author="Matteo Joliveau <matteojoliveau@gmail.com>"

FROM openjdk:8-jdk

COPY --from=0 /usr/local/bin/thrift /usr/local/bin/thrift

RUN apt-get update

