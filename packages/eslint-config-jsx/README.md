# eslint-config-adidas-jsx

Adds ESLint settings for JSX.

## Install

```
npm i --save-dev eslint@4 eslint-config-adidas-jsx
```

## Usage

```json
{
  "extends": [
    "adidas-jsx"
  ]
}
```

Usually you would mix this with other eslint configurations, like:

```json
{
  "extends": [
    "adidas-env/browser",
    "adidas-es6",
    "adidas-jsx"
  ]
}
```

## Links

- [Base configuration](https://tools.adidas-group.com/bitbucket/projects/BWRNPM/repos/pea-linter-configs/browse/packages/eslint-config-es5)
- [ESLint](https://eslint.org/)