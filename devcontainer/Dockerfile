
# FROM ubuntu:latest
FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y 
RUN apt install build-essential -y
RUN apt install git -y
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt-get install curl -y
RUN apt-get install -y sudo
RUN curl -fsSL https://deb.nodesource.com/setup_17.x | sudo -E bash -
RUN sudo apt-get install -y nodejs
RUN npm install --global yarn