# Simple Deploy Mysql

Deploy Mysql:8.0 to Kubernetes Cluster with Helm Chart

```bash
# test
$ helm lint
```

```bash
# deploy
$ helm upgrade --install mysql . --namespace ${KUBE_NAMESPACE} . --wait --atomic
```
