
## Release

```bash
helm package . -d <PATH_TO_helm-charts>
```

## Test

```bash
helm install coturn .
helm test coturn
```
