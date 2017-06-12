# tslint-config-monolambda
[![npm version](https://img.shields.io/npm/v/tslint-config-monolambda.svg?style=flat)](https://www.npmjs.com/package/tslint-config-monolambda)
[![Travis branch](https://img.shields.io/travis/monolambda/tslint-config-monolambda/master.svg)](https://travis-ci.org/monolambda/tslint-config-monolambda.svg?branch=master)
[![Dependency Status](https://gemnasium.com/badges/github.com/monolambda/tslint-config-monolambda.svg)](https://gemnasium.com/github.com/monolambda/tslint-config-monolambda)
[![npm](https://img.shields.io/npm/dt/tslint-config-monolambda.svg)](https://www.npmjs.com/package/tslint-config-monolambda)

## Rules

#### Rule set based on:
- TSLint Latest
- TSLint React
- [TypeScript Standard Style](https://github.com/blakeembrey/tslint-config-standard)

#### Opinions:
- Uses `4, spaces` for easier readability
- Keeps most of the rules but overrides nonpragmatic and artifact focused rules.

**Note:** The current ruleset is subject to change and under review, please feel free to send a PR for rules you feel that are over the top.

## Installation:
```sh
npm install tslint-config-monolambda tslint --save
``` 
## Usage
In `tslint.json`:

```json
{
    "extends": "tslint-config-monolambda"
}
```
