# update-semantic-versioning-action

Github Actions for update semantic versioning.


## Basic usage

```yml
- name: Get next version
  uses: mmrakt/update-semantic-versioning-action@v0.1.0
  with:
    layer: 'minor'
    version: '0.1.0' // bumpup v0.2.0!
```

## with

### layer

which layer of semantic versioning.

e.g. `"major" | "minor" | "pach"`

### version

current semantic version.

e.g. `'0.1.0'`
