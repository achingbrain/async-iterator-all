# it-all

[![Build status](https://travis-ci.org/achingbrain/f.svg?branch=master)](https://travis-ci.org/achingbrain/it-all?branch=master) [![Coverage Status](https://coveralls.io/repos/github/achingbrain/it-all/badge.svg?branch=master)](https://coveralls.io/github/achingbrain/it-all?branch=master) [![Dependencies Status](https://david-dm.org/achingbrain/it-all/status.svg)](https://david-dm.org/achingbrain/it-all)

> Collects all values from an async iterator and returns them as an array

For when you need a one-liner to collect iterable values.

## Install

```sh
$ npm install --save it-all
```

## Usage

```javascript
const all = require('it-all')

// This can also be an iterator, async iterator, generator, etc
const values = [0, 1, 2, 3, 4]

const arr = await all(values)

console.info(arr) // 0, 1, 2, 3, 4
```
