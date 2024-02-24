# installation
```bash
$ git submodule update --init
$ cp .env.template .env
$ docker compose build
$ docker compose run --rm novel-builder bash -c "npm install"
```

# run
```bash
$ docker compose up -d
```

# stop
```bash
$ docker compose down
```

# stop with clear databese
```bash
$ docker compose down --volumes
```