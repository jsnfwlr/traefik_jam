# traefik_jam

1. create a network `docker network create local`
2. run the docker-compose `docker-compose up -d`

the reason for creating an external network is so that you can now have multiple docker-compose files that define various containers, and each of them can use the `local` network so they can be proxied by traefik.
