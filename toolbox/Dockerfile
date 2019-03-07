FROM ubuntu:bionic
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get -y update \
 && apt-get -y install \
               nano \
               python3 \
               python3-pip \
 && pip3 install \
         ansible
COPY .nanorc /root/.nanorc

