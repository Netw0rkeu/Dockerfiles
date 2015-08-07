# nginx with PHP

PHP on an nginx webserver with php-fpm.

### Run

```sh
docker run --name nginx-php -p 80:80 -v /app/persistent/nginx/www:/usr/share/nginx/www -d netw0rkeu/nginx-php:1.0.0
```

### Build version

```sh
docker build -t netw0rkeu/nginx-php:1.0.0 .
```

### Build latest

```sh
docker build -t netw0rkeu/nginx-php:latest .
```

### Versions / Changes

- 1.0.0 - First image (nginx 1.8.0 with PHP 5.5)
