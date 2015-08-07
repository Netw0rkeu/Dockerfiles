# PHPMyAdmin

### Run

```sh
docker run --name phpmyadmin -p 80:80 --link mariadb --env MYSQL_USERNAME=root -d netw0rkeu/phpmyadmin:1.0.0
```

### Build version

```sh
docker build -t netw0rkeu/phpmyadmin:1.0.0 .
```

### Build latest

```sh
docker build -t netw0rkeu/phpmyadmin:latest .
```

### Versions / Changes

- 1.0.0 - First image (phpmyadmin 4.4.12)
