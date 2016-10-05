# koa2-serve-index

  A koa@2 middleware serves pages that contain directory listings for a given path. Based on express [serve-index] 1.8.0

## Install

```sh
$ npm install koa2-serve-index
```

## Usage

```js
const koa = require('koa');
const serve-index = require('koa2-serve-index');
const app = new Koa();

app.use(serve-index(path, options));

app.listen(3000);
```

For more options and API documents, please see [serve-index's README].

## License

[MIT](LICENSE). The [Silk](http://www.famfamfam.com/lab/icons/silk/) icons
are created by/copyright of [FAMFAMFAM](http://www.famfamfam.com/).

[serve-index]: https://github.com/expressjs/serve-index
[serve-index's README]: https://github.com/expressjs/serve-index#serve-index
