# Doctrine

## Migration

### Execute a single migration version up or down manually

*to execute migration version up*
```bash
$ doctrine:migrations:execute YYYYMMDDHHMMSS --up --configuration migration.yml --no-interaction
```

*to execute migration version down*
```bash
$ doctrine:migrations:execute YYYYMMDDHHMMSS --down --configuration migration.yml --no-interaction
```
