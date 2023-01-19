# helm-charts
A repository containing Helm charts for different Kubernetes deployments.

## Charts
* [authzed/spicedb](./charts/spicedb/README.md)

## Installation
```
❯ helm repo add wye0220 https://wye0220.github.io/helm-charts/
❯ helm repo update
❯ helm repo upgrade --install ... <release> wye0220/<chart>
```