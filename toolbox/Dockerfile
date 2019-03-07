FROM ubuntu:bionic
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get -y update \
 && apt-get -y install \
               golang \
               nano \
               python3 \
               python3-pip \
               screen \
               telnet \
 && pip3 install \
         ansible \
         pyvmomi \
         requests \
 && true
COPY .nanorc /root/.nanorc
