# Fullstack


## Getting Started with Docker

https://www.docker.com/get-started

```
$ docker --version
Docker version 18.09.1, build 4c52b90

$ docker-compose --version
docker-compose version 1.23.2, build 1110ad01

$ docker-machine --version
docker-machine version 0.16.1, build cce350d7
```

Run the images
```
docker run hello-world
```

Containers commands
```
$ docker container ls
$ docker container stop webserver
$ docker container ls -a
$ docker container rm webserver
$ docker image ls
$ docker image rm nginx
```

## Docker with Spring Boot

https://spring.io/guides/gs/spring-boot-docker/

## Build and Start the Application

```
./mvnw package && java -jar target/gs-spring-boot-docker-0.1.0.jar
```

Check the website at

http://localhost:8080/



