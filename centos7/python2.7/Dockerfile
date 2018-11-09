FROM centos:centos7

RUN yum install -y epel-release* && yum update -y 

RUN yum install -y which gcc gcc-c++ make 

RUN yum install -y gdal-devel python-devel python-pip 

RUN pip install --upgrade pip 

RUN pip install virtualenv
