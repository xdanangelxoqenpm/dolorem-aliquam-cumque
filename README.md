# @xdanangelxoqenpm/dolorem-aliquam-cumque <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @xdanangelxoqenpm/dolorem-aliquam-cumque
```

## Usage/Examples

```js
var regexTester = require('@xdanangelxoqenpm/dolorem-aliquam-cumque');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@xdanangelxoqenpm/dolorem-aliquam-cumque
[npm-version-svg]: https://versionbadg.es/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque.svg
[deps-svg]: https://david-dm.org/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque.svg
[deps-url]: https://david-dm.org/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque
[dev-deps-svg]: https://david-dm.org/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@xdanangelxoqenpm/dolorem-aliquam-cumque.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@xdanangelxoqenpm/dolorem-aliquam-cumque.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@xdanangelxoqenpm/dolorem-aliquam-cumque.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@xdanangelxoqenpm/dolorem-aliquam-cumque
[codecov-image]: https://codecov.io/gh/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@xdanangelxoqenpm/dolorem-aliquam-cumque
[actions-url]: https://github.com/xdanangelxoqenpm/dolorem-aliquam-cumque/actions
