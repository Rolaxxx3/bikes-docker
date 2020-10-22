# Simple web application for control bikes

## Bootstrapping your environment

```sh
# drop any persistent state to make sure you are working with clean install
$ docker-compose down -v && docker-compose pull
# spin everything up
$ docker-compose up -d
```
Now you should be able to access webclient at http://localhost:8080 and api at http://localhost:8087

### Containers

* [bike-db](https://hub.docker.com/_/mongo)
* [bike-api](https://hub.docker.com/repository/docker/rolaxxx3/bike-api)
* [bike-webclient](https://hub.docker.com/repository/docker/rolaxxx3/bike-webclient)

### GitHub repositories

* [Api](https://github.com/Rolaxxx3/bike-api)
* [Webclient](https://github.com/Rolaxxx3/bike-webclient)

### Requirements

* [Docker 17.06.0+](https://www.docker.com/get-started)
* [Compose 3.0+](https://docs.docker.com/compose/install/)
