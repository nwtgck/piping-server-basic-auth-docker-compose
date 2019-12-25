## Run server

```console
$ cd <this directory>
$ docker-compose up
```

Access to <http://localhost:8080/>. Username is `user1` and password is `1234`.

## Change user and password

Change the following line in [Caddyfile](Caddyfile)

```Caddyfile
...
    basicauth / user1 1234
...
```

See [http.basicauth - Caddy User Guide](https://caddyserver.com/v1/docs/basicauth) to learn more about basic authentication in Caddy.
