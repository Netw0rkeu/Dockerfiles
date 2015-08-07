# MariaDB

### Run

```sh
docker run --name mariadb --env MYSQL_ROOT_PASSWORD=YOUR_ULTRA_SECURE_ROOT_PASSWORD -d netw0rkeu/mariadb:1.0.0
```

### Build version

```sh
docker build -t netw0rkeu/mariadb:1.0.0 .
```

### Build latest

```sh
docker build -t netw0rkeu/mariadb:latest .
```

### Versions / Changes

- 1.0.0 - First image (MariaDB 10.0.20)
