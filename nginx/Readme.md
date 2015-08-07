# nginx

Just a standalone nginx server WITHOUT PHP or other stuff!

### Run

```sh
docker run --name nginx -p 80:80 -v /app/persistent/nginx/html:/usr/share/nginx/html -d netw0rkeu/nginx:1.0.0
```

### Build version

```sh
docker build -t netw0rkeu/nginx:1.0.0 .
```

### Build latest

```sh
docker build -t netw0rkeu/nginx:latest .
```

### Versions / Changes

- 1.0.0 - First image (nginx 1.8.0)
