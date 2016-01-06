# Nodejs Hello-World

FROM ericzon/nodegit:0.2
MAINTAINER Eric Lara <ericzon@gmail.com>
RUN mkdir -p /var/www/nodejs-hello-world
WORKDIR '/var/www/nodejs-hello-world'
RUN git clone https://github.com/ericzon/nodejs-hello-world .
RUN npm install

EXPOSE 3000
	
LABEL version="0.1"
LABEL description="Nodejs Hello World"

