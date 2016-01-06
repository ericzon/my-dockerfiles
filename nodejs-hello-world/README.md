NODEJS-HELLO-WORLD
==================

docker build -t ericzon/nodejs-hello-world .

docker run -it -p 3000:3000 --name nodejs-hello ericzon/nodejs-hello-world
