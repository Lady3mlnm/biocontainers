FROM ubuntu:18.04

MAINTAINER Anton Kulaga <antonkulaga@gmail.com>

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y software-properties-common python3-software-properties automake nano cmake zip wget gcc git build-essential curl gosu

RUN ln -s /usr/bin/python3 /usr/bin/python

# Define default command.
CMD ["/bin/bash"]