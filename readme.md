# Docker + Laravel + MariaDB(MySQL) + nginx

## Required

- Docker

## Description

- Docker -> Virtual environments
- Laravel -> PHP Framework
- MariaDB -> Database
- nginx -> Web server

## Install

Start docker container

```
docker-compose up -d
```

Access for browser

http://localhost:1234

## Database

Use to [Adminer](https://www.adminer.org/)

Access for browser

http://localhost:1234/adminer

## Start Laravel

Document root

/testapp

```
docker-compose exec php-fpm sh
```

```
/var/www/html # cd testapp/
```

```
/var/www/html/testapp # php artisan migrate
```

Access for browser

http://localhost:1234
