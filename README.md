# docker-chrome-stable
Ubunts LTS (16.04) Based chrome stable installed on Docker.

[![Docker Automated buil](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)](https://hub.docker.com/r/teitei/docker-chrome-stable/)
[![Docker Build Statu](https://img.shields.io/docker/build/jrottenberg/ffmpeg.svg)](https://hub.docker.com/r/teitei/docker-chrome-stable/)

## Usage
```bash
$ docker build -t teitei/chrome:latest
$ docker run -it --privileged teitei/chrome bash
```

--privileged option is required

## Dump DOM
```bash
root@f6577517d0b1:/data# google-chrome-stable --headless --disable-gpu --dump-dom https://www.chromestatus.com/
```
