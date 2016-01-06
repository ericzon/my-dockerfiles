# Nodejs + Git + Bower + Grunt + Forever 

FROM ubuntu:latest
MAINTAINER Eric Lara <ericzon@gmail.com>
RUN apt-get -y update
RUN apt-get install -y openssh-client openssh-server python nano git curl build-essential software-properties-common graphicsmagick
RUN curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
RUN apt-get install -y nodejs
RUN npm install -g grunt grunt-cli bower forever

LABEL version="0.1"
LABEL description="First Aid Devtools \
Nodejs + Git + Bower + Grunt + Forever."
