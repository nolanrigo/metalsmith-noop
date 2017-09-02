# metalsmith-noop

[![npm version][version-badge]][version-url]
[![downloads][downloads-badge]][downloads-url]
![wtfpl license][wtfpl-license]

> A metalsmith no-op plugin

## Installation

```bash
$ npm i metalsmith-noop
```

## Exemple

```js
var noop = require('metalsmith-noop');
var plugin = require('metalsmith-plugin');
var isDevelopment = false;

metalsmith(__dirname)
  .use(isDevelopment ? plugin() : noop())
  .build();
```

[downloads-badge]: https://img.shields.io/npm/dm/metalsmith-noop.svg
[downloads-url]: https://www.npmjs.com/package/metalsmith-noop
[version-badge]: https://img.shields.io/npm/v/metalsmith-noop.svg
[version-url]: https://www.npmjs.com/package/metalsmith-noop
[wtfpl-license]: http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-2.png

