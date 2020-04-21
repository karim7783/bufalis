FROM ubuntu:latest

RUN ln -fs /usr/share/zoneinfo/America/Chicago /etc/localtime
RUN apt update
RUN apt -y upgrade
RUN export DEBIAN_FRONTEND=noninteractive && apt -y install python3 python3-pip curl nodejs python3-flask python3-flask-api python3-flask-login python3-flask-restful 
