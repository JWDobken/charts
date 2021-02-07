# jwdobken-charts

My repository for some public helm charts

add with
```cmd
helm repo add jwdobken-charts https://jwdobken.github.io/charts/
```

## lint

helm lint sources/*

## package


helm package sources/*

helm repo index --url https://jwdobken.github.io/charts/ .

git add . && git commit -m "init" && git push origin main
