# ots
onetimesecret

## Docker image

Using **main** branch of [onetimesecret](https://github.com/onetimesecret/onetimesecret) to build the image.

To replace the branch:
```diff
- https://github.com/onetimesecret/onetimesecret/archive/main.tar.gz
+ https://github.com/onetimesecret/onetimesecret/archive/dev.tar.gz
```

## Build

```bash
docker build -t mbwali/onetimesecret:latest .
```

## Helm

### Add helm repo

```bash
helm repo add ots https://mb-wali.github.io/ots/
```
