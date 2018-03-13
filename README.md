docker-compose examples
===========

## Create network

```
docker network create webproxy
```

## Run docker-compose "ingress"

```
cd docker-compose-ingress
docker-compose -f docker-compose.yaml up -d
```

## Run hello-world

```
cd hello-world
# Edit domain and email
vi docker-compose.yaml
docker-compose -f docker-compose.yaml up -d
```

Wait for certificates and open https://<your_domain>