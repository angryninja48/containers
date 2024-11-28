FROM ghcr.io/home-assistant/home-assistant:stable

RUN addgroup -g 1000 homeassistant ; adduser -s /bin/bash -D -h /home/homeassistant -G homeassistant homeassistant ; chown 1000:1000 /home/homeassistant ; chown 1000:1000 /usr/local/lib/python3*/site-packages ; chown 1000:1000 /usr/local/bin /tmp /tmp/*