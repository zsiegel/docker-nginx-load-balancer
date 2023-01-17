# docker-nginx-load-balancer
A simple docker nginx load balancer example

Checkout the full article [here](https://www.zsiegel.com/2022/01/17/Load-balancing-in-docker-with-nginx).

**NOTE** I do not recommend using NGINX for load balancing in Docker Compose. This repo is for demo purposes only. I prefer using Caddy instead. Read about how to do that [here](https://www.zsiegel.com/2022/11/09/load-balancing-in-docker-with-caddy)

```sh
docker-compose up --build --remove-orphans
```
