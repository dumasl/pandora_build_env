FROM ubuntu:19.04

RUN apt-get update

RUN apt-get install -y python3

RUN apt-get update

RUN apt-get -y full-upgrade

RUN apt-get install -y python3-pip --fix-missing

RUN pip3 install --upgrade virtualenv

RUN apt-get install -y gdal-bin libgdal-dev

RUN apt-get clean && \
  rm -rf /var/lib/apt/lists*
