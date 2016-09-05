# docker-node

## build

生产环境
```
docker build -t bilxio/node:0.10 .
```

开发者环境
```
docker build -t bilxio/node:0.10-dev .
```

## publish

```
docker push bilxio/node:0.10-trusty
```

## test

```
docker run --rm bilxio/node:0.10-trusty node -v
```
