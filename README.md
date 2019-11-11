### Wordpress-using-docker-compose

> #### Up and Running a wordpress using docker compose file

* __*Docker Compose is used to run multiple containers as a single service*__

* __*Docker compose file has mainly four parts*__
    - Version
    - services
    - networks
    - volumes

__*This repo has the services MySQL and wordpress that are up and running using Docker Compose.*__

> Install docker compose and give permission to the file 
```
$ curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

$ chmod +x /usr/local/bin/docker-compose
```
> Check syntax and run the docker-compose.yml file
```
$ docker-compose config
$ docker-compose up
```
