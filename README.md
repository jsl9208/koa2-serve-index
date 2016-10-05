# koa2-serve-index

[![NPM version][npm-img]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Build status][travis-img]][travis-url]
[![Test coverage][coveralls-img]][coveralls-url]

  A koa2 middleware serves pages that contain directory listings for a given path, based on Express's [serve-index] v1.8.0.

## Install

```sh
$ npm install koa2-serve-index
```

## Usage

```js
const koa = require('koa');
const serveIndex = require('koa2-serve-index');
const app = new Koa();

app.use(serveIndex(path, options));

app.listen(3000);
```

For more options and API documents, please see [serve-index's README].

## License

[MIT](LICENSE). The [Silk](http://www.famfamfam.com/lab/icons/silk/) icons
are created by/copyright of [FAMFAMFAM](http://www.famfamfam.com/).

[npm-img]: https://img.shields.io/npm/v/koa2-serve-index.svg?style=flat-square
[npm-url]: https://npmjs.org/package/koa2-serve-index
[travis-img]: https://img.shields.io/travis/jsl9208/koa2-serve-index.svg?style=flat-square
[travis-url]: https://travis-ci.org/jsl9208/koa2-serve-index
[coveralls-img]: https://img.shields.io/coveralls/jsl9208/koa2-serve-index.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/jsl9208/koa2-serve-index?branch=master
[downloads-image]: https://img.shields.io/npm/dm/koa2-serve-index.svg?style=flat-square
[serve-index]: https://github.com/expressjs/serve-index
[serve-index's README]: https://github.com/expressjs/serve-index#serve-index
