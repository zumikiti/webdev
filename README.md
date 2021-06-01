# webdev

A set of commonly used services in web development all bundled in a `docker-compose` file.

# Requirements

- docker

# Available Services

- `mysql`
- `redis`
- `meilisearch`
- `mailhog`

# Usage

```bash
$ git clone https://github.com/adwinying/webdev
$ cd webdev
$ copy .env.example .env

# $ docker compose up -d [list services to start up] eg.
$ docker compose up -d mysql mailhog
```
