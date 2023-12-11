# saas-stack

Experiments with microservice based saas stuff

## Compose stack

Trying to keep this as transferable as possible.

```
docker compose up --detach --no-recreate
```

Known issues:

- Container has to create initial databases
- Manual migrations for spicedb need to be run
- Vault dev mode can't have persistence
