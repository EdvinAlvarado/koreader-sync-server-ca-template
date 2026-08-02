# koreader-sync-server-ca-template

Unraid Community Applications template for [KOReader Sync Server](https://github.com/koreader/koreader-sync-server).

## Template URL

```text
https://raw.githubusercontent.com/EdvinAlvarado/koreader-sync-server-ca-template/main/templates/koreader-sync-server.xml
```

## Included defaults

- Docker image: `koreader/kosync:latest`
- HTTPS listener: container port `7200`
- Persistent Redis data: `/mnt/user/appdata/koreader-sync-server/data/redis`
- Optional log paths:
  - `/mnt/user/appdata/koreader-sync-server/logs/app`
  - `/mnt/user/appdata/koreader-sync-server/logs/redis`
