# About

My personal shareable/reusable eslint config for node/express apps.

# Usage

## New project:

`npm init @eslint/config -- --config @9akashnp8/eslint-config-node`


## Existing Project

1. `npm install @9akashnp8/eslint-config-node`

2. Create the eslint config file (`.eslintrc.{js,yml,json}`) in your root dir and extend from this config

```json
{
    "extends": "eslint:recommended"
}
```
