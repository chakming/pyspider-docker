# pyspider-docker
pyspider quick start


### Pre-requisite
- [install docker & docker-compose](https://medium.com/@whitepolarbear/docker-setup-in-mac-in-a-minute-sep-2016-ff4f6a0d6070#.831c3typ6)

### Steps
- Clone this repo
- start mysql: `docker run --name mysql -d -v /data/mysql:/var/lib/mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=yes mysql:latest`
- start rabbitmq: `docker run --name rabbitmq -d rabbitmq:latest`
- `docker-compose up` and done!
```
