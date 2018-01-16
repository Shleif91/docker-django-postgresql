FROM python:3

RUN mkdir /data
ADD requirements.txt /data
RUN pip install -r requirements.txt
ADD . /data
WORKDIR /data
