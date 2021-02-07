# helm-hasura

Chart for the graphql-engine [Hasura](https://hasura.io/)

## Testing

test locally:

```cmd
helm install -n hasura --dry-run --debug hasura . > test.yaml
```

Or deploy:

```cmd
helm upgrade --install -n hasura hasura .
```
