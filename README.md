# Cyber Security

## Owner
- 4820750141
- Prawee Wongsa
- prawee.w@fte.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running services
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

### Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```

### Application
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # background
```