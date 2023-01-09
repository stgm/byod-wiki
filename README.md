# BYOD Wiki

## Lokale server

Zorg dat je `docker-ce` met `docker-compose-plugin` (v2) hebt geïnstalleerd.
```
BUILDKIT_PROGRESS=plain docker compose -f docker-compose.dev.yaml up --build --force-recreate
```

Server is nu toegankelijk op http://localhost:8080
