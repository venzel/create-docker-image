# README.md

## Create build

```bash
docker build -t venzel/my_app .
```

## Update build, tag

```bash
docker build -t venzel/my_app:v2 .
```

## Run

```bash
docker run --name my_app_container -d -p 3000:3000 venzel/my_app
```

## Copy file

```bash
docker cp my_app_container:/app/src/app.js /mnt/ext/app.js
```

## Access container

```bash
docker exec -it my_app_container /bin/bash
```

## Docker push

```bash
docker push venzel/my_app:v2
```
