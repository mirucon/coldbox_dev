# coldbox_dev

Coldbox dev env with [wp_docker_config](https://github.com/mirucon/wp_docker_config).

Start dev with `$ docker-compose up -d`.

Ports:

* localhost:6507 for WordPress itself
* localhost:6597 for MySQL
* localhost:6525 for mailcatcher GUI, :6580 for mail port

## WP-CLI

```bash
$ docker-compose run --rm cli wp [command]
```
