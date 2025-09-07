# Flarum docker env

## Add local repository

```bash
composer config repositories.0 path "extensions/*"
```

## Debug mode

copy and mount flarum config to toggle debug

## Extensions

- git clone, to extensions folder
- run in terminal, docker compose exec php composer require ...

## Flarum commands

executed with `docker compose exec php php flarum ...` (yes, twice php. first is the service name, second is the command to run inside it)

## SSL

i use mkcert to issue self-signed certificates
