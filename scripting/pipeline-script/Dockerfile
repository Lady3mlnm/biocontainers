FROM quay.io/comp-bio-aging/ammonite:latest

LABEL maintainer="antonkulaga@gmail.com"

ADD predefShared.sc /root/.ammonite/

RUN echo 'println("loaded dependencies")' > /data/init.scala && /usr/local/bin/amm /data/init.scala && rm /data/init.scala
RUN mkdir /scripts
ENV PATH /scripts:$PATH
