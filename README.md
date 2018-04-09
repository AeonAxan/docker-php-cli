Docker: PHP and extensions
==========================

Official [PHP docker image](https://hub.docker.com/_/php/) with additional extensions.

Supported tags
--------------

| PHP Version | Tags            |
| ----------- | --------------- |
| 7.1.1       | `7.1`, `latest` |
| 7.0.15      | `7.0`           |
| 5.6.30      | `5.6`           |

Extensions
----------

- mcrypt
- iconv
- intl
- mbstring
- gd
- curl
- dom
- soap
- simplexml
- xmlreader
- xmlwriter
- sockets
- zip
- mysqli
- pdo_mysql
- pdo_sqlite
- memcached
- redis
- simplexml
- apcu
- opcache
- ftp
- gearman *(PHP 5.6 only)*

Resources
---------

- composer
- phpunit
- wget
- vim
- git
- unzip

Build
---------

```
  # build 5.6 image
  cd 5.6
  docker build -t merorafael/docker-php:5.6 .
```
