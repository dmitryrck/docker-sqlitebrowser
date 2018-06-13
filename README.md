# sqlitebrowser using docker

Runing:

```terminal
$ docker run --rm \
  -e DISPLAY=unix:0 \
  -v /dev/shm:/dev/shm \
  -v ${HOME}:/${USER} \
  -v /tmp/.X11-unix:/tmp/.X11-unix \
  dmitryrck/sqlitebrowser sqlitebrowser
```
