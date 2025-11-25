# ESB Example with Zato

With reference to the guide at [the Zato Blueprint](https://github.com/zatosource/zato-project-blueprint).

Find the documentation for this [here](https://zato.io/en/docs/4.1/admin/guide/install/docker.html).

## Configure

```
cp .env.example .env
```

Then fill `.env` with values.

## Run

```bash
docker compose up -d
```

## Restart

_Mind that changes will be lost due to the way Zato implements their Test Env._

```bash
docker compose up -d --force-recreate
```

## Stop

```bash
docker compose down
```