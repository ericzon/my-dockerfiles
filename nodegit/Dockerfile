# Nodejs + Git + Bower + Grunt + Forever 

FROM ubuntu:latest
MAINTAINER Eric Lara <ericzon@gmail.com>
ENV NODE_ENV development
RUN apt-get -y update
RUN apt-get install -y openssh-client openssh-server
RUN apt-get install -y git
RUN apt-get -y install curl
RUN curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
RUN apt-get install -y nodejs
RUN apt-get install -y build-essential
RUN npm install -g grunt grunt-cli
RUN npm install -g bower
RUN npm install -g forever
RUN apt-get install -y nano

RUN mkdir -p /var/www/
WORKDIR '/var/www/nodejs-hello-world'
RUN git clone https://github.com/ericzon/nodejs-hello-world .
RUN npm install

EXPOSE 5000:3000

# ENTRYPOINT ['forever']
# CMD ['node', 'index.js']