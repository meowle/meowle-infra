# Setup meowle infrastructure

## Steps

1. Clone this repo to working directory.
2. Create directory `./.data`.
3. Create file `./.data/vscale-api-token` with VScale API Token. It's required for Let's Encrypt certs.
4. Create file `./.data/kibana-basic-auth` with [users for Kibana](https://docs.traefik.io/v2.0/middlewares/basicauth/#usersfile).
5. Start docker containers with command `docker-compose up -d`.
