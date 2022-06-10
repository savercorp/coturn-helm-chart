# coturn-helm-chart

## Prerequisites

- [Helm](https://helm.sh) is installed
-
## Installation

You can install it by one line:

```bash
helm upgrade --install coturn coturn \
  --repo https://savercorp.github.io/helm-charts
```

Or step by step:

```bash
helm repo add saver https://savercorp.github.io/helm-charts
helm install coturn saver/coturn
```

## Contributing

Please read through our [contributing guidelines](/CONTRIBUTING.md).
