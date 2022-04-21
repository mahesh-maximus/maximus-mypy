
FROM ubuntu:latest
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y 
RUN apt install build-essential -y
RUN apt install git -y
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt-get install curl -y
RUN curl -fsSL https://deb.nodesource.com/setup_17.x | bash -
RUN apt-get install -y nodejs -y
