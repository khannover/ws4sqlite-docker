# ws4sqlite-docker

[ws4sqlite](https://github.com/proofrock/ws4sqlite) in Docker

Using alpine as base image.

## Getting started

Run inside armv7 or linux-x64 folder

```bash
docker build -t ws4sqlite .
docker run -d -p 8080:12321 --name ws4sqlite -v $(pwd)/data:/database ws4sqlite
```
