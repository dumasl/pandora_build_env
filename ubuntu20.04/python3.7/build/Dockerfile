FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install -y --no-install-recommends apt-utils

RUN apt-get install -y python3

RUN apt-get update

RUN apt-get -y full-upgrade

RUN apt-get install -y python3-pip --fix-missing

RUN pip3 install --upgrade virtualenv

RUN apt-get install -y gdal-bin libgdal-dev

# opencv dependencies
RUN apt-get install -y libsm6 libxrender1 libxext6

# git for git_scm version
RUN apt-get install -y git

# clean up
RUN apt-get clean && \
  rm -rf /var/lib/apt/lists*
