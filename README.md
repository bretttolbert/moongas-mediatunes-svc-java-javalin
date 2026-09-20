# Moongas

## Moongas Mediatunes API Service (Java / Javalin)

Lightweight music collection server. Java/Javalin port of the original Python
BlackSheep implementation
([moongas-mediatunes-svc-python-blacksheep](https://github.com/bretttolbert/moongas-mediatunes-svc-python-blacksheep)),
serving the same JSON API from a mediascan SQLite database.

### Configuration

Configuration is loaded from a YAML file passed as the first command line
argument (or from the `MEDIATUNES_CONFIG` environment variable). See
[mediatunes-config.yml](mediatunes-config.yml) for the available options.

### Running

```
./gradlew mediatunes-svc:run --args="mediatunes-config.yml"
```

### Testing

```
./gradlew mediatunes-svc:test
```
