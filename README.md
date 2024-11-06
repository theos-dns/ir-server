# theos ir server

## run
```bash
$ docker compose rm -f
$ docker compose up -d
```

## Generate SSL certs for DoH and DoT
Fallow this instruction to create ssl for your domain : [acme.sh](https://github.com/acmesh-official/acme.sh)

put `key.pem` and `cert.pem`(fullchain.cer) files in [`ssl-keys`](./ssl-keys).