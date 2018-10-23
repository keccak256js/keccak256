# keccak256

> A wrapper for the [keccak](https://www.npmjs.com/package/keccak) library to compute 256 bit keccak hash in JavaScript.

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/miguelmota/keccak256/master/LICENSE.md) [![Build Status](https://travis-ci.org/miguelmota/keccak256.svg?branch=master)](https://travis-ci.org/miguelmota/keccak256) [![Coverage Status](https://coveralls.io/repos/github/miguelmota/keccak256/badge.svg?branch=master)](https://coveralls.io/github/miguelmota/keccak256?branch=master) [!(https://img.shields.io/appveyor/ci/miguelmota/keccak256.svg?branch=master&style=flat-square)](https://ci.appveyor.com/project/miguelmota/keccak256)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Install

```bash
npm install keccak256
```

## Getting Started

```js
const keccak256 = require('keccak256')

console.log(keccak256('hello').toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"

console.log(keccak256(Buffer.from('hello')).toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"
```


## Test

```bash
npm test
```

## License

MIT
