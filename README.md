# webdev

A set of commonly used services in web development all bundled in a `docker-compose` file.

# Requirements

- docker

# Available Services

- `mysql`
- `pgsql`
- `redis`
- `meilisearch`
- `mailhog`
- `pgweb`

# Usage

```bash
$ git clone https://github.com/adwinying/webdev
$ cd webdev

# $ docker compose up -d [list services to start up] eg.
$ docker compose up -d mysql mailhog
```
