# GHGA GitHub Action CI

This GitHub Action encapsulates common steps that are executed in GitHub Action workflows within the GHGA CI pipeline. Use as follows:

```yaml
- id: CI
  uses: ghga-de/gh-action-ci@v1
```

## Test action
```shell
act -W test -s DOCKERHUB_USERNAME=*** -s DOCKERHUB_TOKEN=*** -e test/event.json
```
