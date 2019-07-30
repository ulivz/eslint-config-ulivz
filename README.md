# ESLint config for ulivz

[![Greenkeeper badge](https://badges.greenkeeper.io/ulivz/eslint-config-ulivz.svg)](https://greenkeeper.io/)

This config is supposed to work with [XO](https://github.com/sindresorhus/xo) or [eslint-config-xo](https://github.com/sindresorhus/eslint-config-xo).

> modified from [eslint-config-rem](https://github.com/egoist/eslint-config-rem)

## Features

- Indent with 2 spaces and no semicolon
- [Prettier!](#use-prettier)
- [Lint code blocks in Markdown!](#lint-code-blocks-in-markdown)
- ...some tweaks for my preference.

## Install

```bash
$ npm install -D eslint eslint-config-rem
```

## Usage

In ESLint:

```js
{
  "eslintConfig": {
    "extends": ["xo/esnext", "rem"]
  }
}
```

Or in XO:

```js
{
  "xo": {
    "extends": "rem"
  }
}
```

### Use Prettier

```js
{
  "xo": {
    "extends": "rem/prettier"
  }
}
```

### Lint code blocks in markdown

It uses [eslint-plugin-markdown](https://github.com/eslint/eslint-plugin-markdown):

```js
{
  "xo": {
    "extensions": ["md"]
  }
}
```
