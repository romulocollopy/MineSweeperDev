## MineSweeperDev

Run projects:

```console
cp .env-example .env
git submodule init git submodule update
docker compose up -d
docker compose exec api python manage.py migrate
```

Access `http://localhost:3000` or `http://www.localhost:8880`
