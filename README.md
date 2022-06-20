### Howto update index.yaml
```
helm repo index --url https://kingpowerclick.github.io/helm-chart/package/ ./package/

mv package/index.yaml index.yaml

```

### Add repo
```
helm repo add kpc-helm https://kingpowerclick.github.io/helm-chart
```

