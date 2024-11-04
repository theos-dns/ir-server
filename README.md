# theos ir server

## run
```bash
$ docker compose rm -f
$ docker compose up -d
```

## Generate SSL certs for DoH and DoT
Fallow this instruction to create ssl for your domain in cloudflare: [cloudflare client certificate](https://developers.cloudflare.com/ssl/client-certificates/create-a-client-certificate/)

put `key.pem` and `cert.pem` files in [`ssl-keys`](./ssl-keys).