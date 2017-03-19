# docker-rpi-certbot - Docker image for Certbot (letsencrypt) on a raspberrypi
![Travis build status](https://api.travis-ci.org/mahnkong/docker-rpi-certbot.svg?branch=master)

## Usage

A typical invocation of the container would be:
```
docker run -it --rm -v "/var/lib/letsencrypt:/var/lib/letsencrypt" -v "/etc/letsencrypt:/etc/letsencrypt"  --volumes-from my_nginx mahnkong/docker-rpi-certbot renew
```
