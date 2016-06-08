# Doctrine

## Migration

### Execute a single migration version up or down manually

*to execute migration version up*
```shell
$ doctrine:migrations:execute YYYYMMDDHHMMSS --up --configuration migration.yml --no-interaction
```

*to execute migration version down*
```shell
$ doctrine:migrations:execute YYYYMMDDHHMMSS --down --configuration migration.yml --no-interaction
```
