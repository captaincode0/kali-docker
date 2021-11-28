# kali-docker

Dockerized Kali Linux Environment with kalilinux/kali official image

# Setup

```
# headless
docker compose build
docker compose run --rm kali bash

# large
KALI_TOOLKIT=large docker compose build
KALI_TOOLKIT=large docker compose run --rm kali bash
```

For `KALI_TOOLKIT` please find in [Kali DockerHub](https://hub.docker.com/r/kalilinux/kali) page.

# Run

```
export KALI_TOOLKIT=large # not needed for normal run

./shell.sh
```