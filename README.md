### pgclient

```
$ docker build --no-cache -t eshlee/pgclient:9.5-alpine -f Dockerfile-9.5 .
$ docker build --no-cache -t eshlee/pgclient:9.6-alpine -f Dockerfile-9.6 .

docker push eshlee/pgclient:9.5-alpine
docker push eshlee/pgclient:9.6-alpine
```
