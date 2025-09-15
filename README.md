# dbt-core
dbt-core docker image for ARM

### Setup Docker Builder
```
docker buildx create --name mybuilder --bootstrap --use
```


### OS
```
docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 -t ghcr.io/neekipatel/dbt-core/dbt:latest . --push
```
