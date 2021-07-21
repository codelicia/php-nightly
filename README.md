# php-nightly
A container image with the nightly version of the PHP (in development) to test the new features, give feedback and keep CI looking for upgrading issues.

## Docker HUB

```bash
docker run -it --rm codelicia/php-nightly:latest php --version
```

## Github Registry

```bash
docker run -it --rm ⁨ghcr.io/codelicia/php-nightly:master php --version
```
