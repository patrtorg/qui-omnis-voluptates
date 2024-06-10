# @patrtorg/qui-omnis-voluptates <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@patrtorg/qui-omnis-voluptates');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@patrtorg/qui-omnis-voluptates
[npm-version-svg]: https://versionbadg.es/inspect-js/@patrtorg/qui-omnis-voluptates.svg
[deps-svg]: https://david-dm.org/inspect-js/@patrtorg/qui-omnis-voluptates.svg
[deps-url]: https://david-dm.org/inspect-js/@patrtorg/qui-omnis-voluptates
[dev-deps-svg]: https://david-dm.org/inspect-js/@patrtorg/qui-omnis-voluptates/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@patrtorg/qui-omnis-voluptates#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/qui-omnis-voluptates.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/qui-omnis-voluptates.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/qui-omnis-voluptates.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/qui-omnis-voluptates
[codecov-image]: https://codecov.io/gh/inspect-js/@patrtorg/qui-omnis-voluptates/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@patrtorg/qui-omnis-voluptates/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@patrtorg/qui-omnis-voluptates
[actions-url]: https://github.com/patrtorg/qui-omnis-voluptates/actions
