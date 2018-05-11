# eslint-config-adidas-es7

ES7 (ES2016) ESLint rules.

These already extend `eslint-config-adidas-es6`.

This set of rules is not too restrictive since ES7 features are yet in evaluation.

## Install

```
npm i --save-dev eslint@4 eslint-plugin-import@2 eslint-plugin-promise@3 eslint-config-adidas-es5 eslint-config-adidas-es6 eslint-config-adidas-es7
```

## Usage

```json
{
  "extends": [
    "adidas-es7"
  ]
}
```

Usually you would mix this with other eslint configurations, like:

```json
{
  "extends": [
    "adidas-env/browser",
    "adidas-env/modules",
    "adidas-es7"
  ]
}
```

## Links

- [Base configuration](https://tools.adidas-group.com/bitbucket/projects/BWRNPM/repos/pea-linter-configs/browse/packages/eslint-config-es5)
- [ESLint](https://eslint.org/)