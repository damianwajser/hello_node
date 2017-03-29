# hello_node

## build docker 
docker build -t dami/hello_node:0.1 .

## run docker
docker run -e KEY=123 -p 4000:4000 dami/hello_node:0.1

