# Nodejs + Git + Bower + Grunt + Forever 

FROM ubuntu:latest
MAINTAINER Eric Lara <ericzon@gmail.com>
RUN apt-get -y update
RUN apt-get install -y openssh-client openssh-server
RUN apt-get install -y git
RUN apt-get -y install curl build-essential python software-properties-common graphicsmagick
RUN curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
RUN apt-get install -y nodejs
RUN apt-get install -y build-essential
RUN npm install -g grunt grunt-cli
RUN npm install -g bower
RUN npm install -g forever
RUN apt-get install -y nano

LABEL version="0.1"
LABEL description="First Aid Devtools \
Nodejs + Git + Bower + Grunt + Forever."
