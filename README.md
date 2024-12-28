## Timezone check

```
realpath --relative-to /usr/share/zoneinfo /etc/localtime
```
Replace to **`docker-compose.yaml`**
## Install Chromium

**1. Create directory**

    mkdir chromium
    cd chromium

**2.Create  `docker-compose.yaml`  file**

    nano docker-compose.yaml
Paste content of   `docker-compose.yaml` then Ctrl + O -> Enter -> Ctrl + X
## Run Chromium

    cd $HOME && cd chromium
    docker compose up -d

## Optional: Stop and Delete Chromium

    docker stop chromium
    docker rm chromium
    docker system prune
**To access your Chromium, go to address (Remember not https if your server not configured for https !!!!)**

    http://VPS-IP:3010
    http://VPS-Ip:3011

