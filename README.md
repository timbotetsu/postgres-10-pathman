# PostgreSQL docker image with pg_pathman

This is a docker image based on [offical postgres image](https://hub.docker.com/_/postgres/), which could accept environment variables as the offical image, but with [pg_pathman](https://github.com/postgrespro/pg_pathman) installed.

# Version
* Postgres - 10.5
* pg_pathman - 1.4.13

# Usage

Use this image just like the offical postgres image.

To starting a Postgres Instance with a specified username and password, run as following:

```
$ docker run -d --name some-postgres -p 5432:5432 -e POSTGRES_USERNAME=username -e POSTGRES_PASSWORD=password timbotetsu/postgres-10-pathman
```

More details, please reference to [documentations](https://hub.docker.com/_/postgres/).
