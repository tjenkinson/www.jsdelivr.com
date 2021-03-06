# [www.jsdelivr.com](https://www.jsdelivr.com)

[![Build Status](https://img.shields.io/travis/jsdelivr/www.jsdelivr.com.svg?style=flat-square)](https://travis-ci.org/jsdelivr/www.jsdelivr.com)
[![dependencies](https://img.shields.io/david/jsdelivr/www.jsdelivr.com.svg?style=flat-square)](https://david-dm.org/jsdelivr/www.jsdelivr.com)
[![devDependencies](https://img.shields.io/david/dev/jsdelivr/www.jsdelivr.com.svg?style=flat-square)](https://david-dm.org/jsdelivr/www.jsdelivr.com?type=dev)

Related projects:
 - [jsDelivr CDN](https://github.com/jsdelivr/jsdelivr)
 - [jsDelivr API](https://github.com/jsdelivr/data.jsdelivr.com)

## Development

```
$ npm install
$ node src
```

## Production config

```js
module.exports = {
    server: {
        port: 'SERVER_PORT', // defaults to 4400
    },
}
```

Additionally, opbeat token should be set via `OPBEAT_TOKEN` variable, and `NODE_ENV=production`.

Staging: https://jsdelivr-com.herokuapp.com/
