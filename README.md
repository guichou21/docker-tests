# docker-tests (Nginx, PHP FPM, MySQL)

## Data
PHP files are in /front/www

Static files are in /front/www

## Conf file

## Logs


## How To
### Start
```
docker-compose up -d
```

Builds, (re)creates, starts, and attaches to containers based on docker-compose.yml.


**Access to the website**:
```
docker-machine ip
```
http://<ip>:8080


### Logs
```
docker-compose logs
```

Display containers logs (More logs in front/logs)


### Stop
```
docker-compose stop
```

Stops running containers without removing them.

They can be started again with ```docker-compose start```.

### Delete
```
docker-compose rm
```

Removes stopped service containers



## TODO
Memcache
un repertoire data/mysql, data/php, ...?

PHP files in /data/php

Static files are in /data/nginx
