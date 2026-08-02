# koreader-sync-server-ca-template

Unraid Community Applications template for [KOReader Sync Server](https://github.com/koreader/koreader-sync-server).

## Template URL

```text
https://raw.githubusercontent.com/EdvinAlvarado/koreader-sync-server-ca-template/main/templates/koreader-sync-server.xml
```

## Included defaults

- Docker image: `koreader/kosync:latest`
- HTTPS listener: container port `7200`
- Persistent Redis data: `/mnt/user/appdata/kosync/data/redis`
- Optional log paths:
  - `/mnt/user/appdata/kosync/logs/app`
  - `/mnt/user/appdata/kosync/logs/redis`
