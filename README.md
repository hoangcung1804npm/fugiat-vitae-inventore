# @hoangcung1804npm/fugiat-vitae-inventore <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@hoangcung1804npm/fugiat-vitae-inventore');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hoangcung1804npm/fugiat-vitae-inventore
[npm-version-svg]: https://versionbadg.es/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore.svg
[deps-svg]: https://david-dm.org/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore.svg
[deps-url]: https://david-dm.org/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore
[dev-deps-svg]: https://david-dm.org/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hoangcung1804npm/fugiat-vitae-inventore.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hoangcung1804npm/fugiat-vitae-inventore.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hoangcung1804npm/fugiat-vitae-inventore.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hoangcung1804npm/fugiat-vitae-inventore
[codecov-image]: https://codecov.io/gh/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@hoangcung1804npm/fugiat-vitae-inventore
[actions-url]: https://github.com/hoangcung1804npm/fugiat-vitae-inventore/actions
