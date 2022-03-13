# glowing-parakeet
Publishing a package with npm, github actions, semantic release and conventional commits


**Note**: this package is not made for actual use.

# Actions used

### [Checkout](https://github.com/actions/checkout)

To be used whenever you are using Github actions. 

Allows github workflows to be used.

### [Node](https://github.com/actions/setup-node)

To be used whenever you are using node. It allows you to cache the node modules, also test in different versions of node.

### [Commitlint](https://github.com/wagoid/commitlint-github-action)

Lints pull requests with [Commitlint](https://commitlint.js.org/#/)


## Github expresssions

Github expressions come in the format:

```yaml
if: ${{ <expression> }}
```

## Publish / Release

## linting commits

See the [commitlint](.github/workflows/commitlint.yml).

