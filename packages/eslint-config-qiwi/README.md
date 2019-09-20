# eslint-config-qiwi
[![Build Status](https://travis-ci.com/qiwi/tslint-config-qiwi.svg?branch=master)](https://travis-ci.com/qiwi/tslint-config-qiwi)
[![npm (tag)](https://img.shields.io/npm/v/tslint-config-qiwi/latest.svg)](https://www.npmjs.com/package/tslint-config-qiwi)
[![dependencyStatus](https://img.shields.io/david/qiwi/tslint-config-qiwi.svg?maxAge=300)](https://david-dm.org/qiwi/tslint-config-qiwi)
[![Test Coverage](https://api.codeclimate.com/v1/badges/e7fdc4e135133bfb5370/test_coverage)](https://codeclimate.com/github/qiwi/tslint-config-qiwi/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/e7fdc4e135133bfb5370/maintainability)](https://codeclimate.com/github/qiwi/tslint-config-qiwi/maintainability)

[ESLint](https://eslint.org) rules related to QIWI projects.

## Install
```bash
npm add eslint-config-qiwi -D
yarn add eslint-config-qiwi -D
```

## Usage
Refer to `eslint-config-qiwi` in your [.eslintrc.json](https://eslint.org/docs/user-guide/configuring):
```json
{
  "extends": "eslint-config-qiwi"
}
```
[Run](https://palantir.github.io/tslint/usage/cli/) linting your TS code:
```bash
eslint -c /any/path/to/.eslintrc.json --fix
```

## Contribution
If you find this config not strong enough you may add additional rules, write some tests, and trigger assets generation.
```bash
yarn test:gen
```