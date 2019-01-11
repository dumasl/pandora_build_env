FROM ubuntu:19.04

RUN apt-get update

RUN apt-get install -y python python-pip

RUN pip install --upgrade virtualenv

RUN apt-get install -y gdal-bin libgdal-dev

RUN apt-get clean && \
  rm -rf /var/lib/apt/lists*
