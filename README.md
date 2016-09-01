## build

```
docker build -t bilxio/track-coffee:0.10 .
```

tag
```
docker tag <imageID> <namespace>/<image name>:<version tag eg latest>
```

## test

print version

```
docker run --rm bilxio/track-coffee:0.10 coffee -v

docker run --rm bilxio/track-coffee:0.10 which zip
docker run --rm bilxio/track-coffee:0.10 which unzip
```

run some coffee

```
docker run --rm -v `pwd`:/app bilxio/track-coffee:0.10
docker run --rm -v `pwd`:/app bilxio/track-coffee:0.10
```
