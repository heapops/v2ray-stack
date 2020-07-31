v2ray compose
====

Support parameters(server ip, server port, id) passed by env.

If env V2RAY_ID is not set, use default ```/etc/v2ray/config.json```.

### usage

* cp v2ray.secret.example to v2ray.secret and change the id.

* docker-compose,

```bash
docker-compose up -d
```
