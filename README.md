# jwdobken-charts

some of my public helm charts

To add these Charts for your local client, run helm repo add:

```cmd
$ helm repo add jwdobken-charts https://jwdobken.github.io/charts/
"jwdobken-charts" has been added to your repositories
```

## lint

```cmd
helm lint sources/*
```

## add new charts to the repo

Put the chart in the sources folder and recreate the index file with:

```cmd
helm package sources/*
helm repo index --url https://jwdobken.github.io/charts/ --merge index.yaml .
```
