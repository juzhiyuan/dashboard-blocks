# dashboard-blocks

Blocks for Dashboard, based on [Umi.js](https://umijs.org/).

## Development

### Create a [block](https://v2.umijs.org/zh/guide/block.html)

```bash
# Use block template then modify package.json if needed (recommended)
$ cp -r BlockTemplate TargetBlock

# Use umi.js
$ mkdir TemplateBlock && cd TemplateBlock
$ yarn create umi --type=block
```

### Run

```bash
$ yarn start [BlockName]

# e.g
$ yarn start BlockTemplate
```

## Note

1. `umi-block.json` will be updated automatically when you push changes to GitHub, so please DO NOT change the file manually.
