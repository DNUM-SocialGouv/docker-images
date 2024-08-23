# Docker base images

## nginx4spa

Based on https://github.com/SocialGouv/docker/tree/master/nginx4spa

Add the possibility to run the SPA with runtime env variables:

- generate config.json at runtime, at nginx root dir
- static frontend SPA can fetch thie config file, without depending on build args to generate the static files (ex. Next, Nuxt, etc.)
