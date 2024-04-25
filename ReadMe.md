
# Example of Containerization

## Run following command on terminal

docker build --tag=hello_docker .

docker build -t hello_docker .

docker image ls

docker run -p 4000:80 hello_docker

docker container stop CONTAINER_ID

docker container ls
