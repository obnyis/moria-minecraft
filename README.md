# Moria Minecraft

## Requires:
`.env`
`moria.env`
`secrets/rcon_password`

## Setup:
```
nano .env
nano moria.env
nano secrets/rcon_password
git submodule update --init --recursive
docker-compose up -d
```

## .env Sample:

```
MORIA_HOST=
MODPACK_TLD=
WEBSITE_TLD=
DYNMAP_TLD=
MINECRAFT_PORT=
RCON_PORT=

TRAEFIK_PACKWIZ=
TRAEFIK_WEBSITE=
TRAEFIK_DYNMAP=
```

## moria.env Example:

```
OPS=""
WHITELIST=""
SEED=""
```

