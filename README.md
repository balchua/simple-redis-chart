# Deploy simple redis charts

``` bash
helm upgrade --install --create-namespace --namespace redis redis -f values-local.yaml .
```


# Uninstall

```bash
helm uninstall --namespace redis redis
```