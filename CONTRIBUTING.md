# CONTRIBUTING

## Install from local source

Clone the repository and execute in the repository.

```bash
helm install coturn .
```

## Update dependencies

Rebuild the charts/ directory based on the Chart.lock file.

```bash
helm dependency build
```

## Test

Install from local source and test connection.

```bash
helm install coturn .
helm test coturn
```

## Versioning

Follow semantic versioning 2.

Edit `Chart.yaml`.

```yaml
...
version: 1.2.3 # Chart version
...
appVersion: "4.5.2" # Coturn version
...
```

Create git tag.

```bash
git tag v1.2.3
git push origin v1.2.3
```
