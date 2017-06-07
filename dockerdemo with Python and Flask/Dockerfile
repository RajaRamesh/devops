# ref: http://odewahn.github.io/docker-jumpstart/building-images-with-dockerfiles.html
#
# Super simple example of a Dockerfile
#
FROM ubuntu:latest
MAINTAINER Raja "cloudify19@gmail.com"

RUN apt-get update
RUN apt-get install -y python python-pip wget
RUN pip install Flask

ADD hello.py /home/hello.py
ADD test9.py /home/test9.py

WORKDIR /home
