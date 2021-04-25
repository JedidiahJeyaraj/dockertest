# dockertest
Just a docker test app
Use the below commands to check few things:

1. `docker ps` to check all the running docker containers
2. `docker build -t jedidiahjeyaraj/dockertest:1.0 .` to build an image
3. `docker run -p 5000:5000 jedidiahjeyaraj/dockertest:1.0` to run the build docker image
4. If building using docker-compose use `docker-compose up`
5. To enter into a particular docker container using shell use `docker exec -it {container_id} /bin/bash`
6. To Create a volume use `docker volume create {volume_name}`
