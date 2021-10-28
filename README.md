# docker_unmanic

```shell
docker run -d \
    --restart=unless-stopped \
    --name=unmanic \
    -e PUID=${PUID} \
    -e PGID=${PGID} \
    -e TZ=Europe/Zurich \
    -p 8888:8888 \
    -v /path/to/unmanic/config:/config \
    -v /path/to/unmanic/library:/library \
    -v /path/to/unmanic/temp:/tmp/unmanic \
    josh5/unmanic:latest
```
