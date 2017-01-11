FROM python:2.7

RUN sed -i 's/deb.debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list
RUN apt-get update

RUN mkdir /usr/src/app
WORKDIR /usr/src/app
ADD requirements.txt /usr/src/app/

ADD pip.conf /root/.pip/pip.conf
RUN pip install -r requirements.txt

ADD . /usr/src/app/
