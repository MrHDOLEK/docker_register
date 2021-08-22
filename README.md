# Docker_register

## How to run?
 1. Clone repo
 2. Change mail for nginx-cerbot.env and docker-compose.yml
 3. Change serwer_name , ip_serwer for `.docker/nginx/conf.d/default.conf`
 4. `$ docker compose up`
 5. Go to auth/registry.htpasswd and change user:pass ([Generate htpasswd](https://hostingcanada.org/htpasswd-generator/)) use mode a bcrypt

## Useful commands for using docker registry

 - `$ docker login <ip_serwer/domain> -u <login>` 
 - `$ docker push busybox:latest <ip_serwer/domain> -u <login>`