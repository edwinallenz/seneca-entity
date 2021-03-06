![Seneca Entity](http://senecajs.org/files/assets/seneca-logo.png)

> _Seneca Entity_ is an entity plugin for [Seneca](http://senecajs.org)

# Seneca Entity
[![npm version][npm-badge]][npm-url]
[![Build Status][travis-badge]][travis-url]
[![Dependency Status][david-badge]][david-url]
[![Coveralls][BadgeCoveralls]][Coveralls]
[![Gitter][gitter-badge]][gitter-url]

Lead Maintainer: [Wyatt Preul](https://github.com/geek)

If you're using this module, and need help, you can:

- Post a [github issue][],
- Tweet to [@senecajs][],
- Ask on the [Gitter][gitter-url].

### Seneca compatibility
Supports Seneca versions **1.x** - **3.x**

## Install
To install, simply use npm.


```
npm install seneca-entity
```

if your're using seneca-entity >= 1.3.0 you must install seneca-basic package

```
npm install seneca-entity seneca-basic
```


## Using Seneca Entity

```js
require('seneca')()
  .use('entity')
```

### For version >= 1.3.0

```js
require('seneca')()
  .use('entity')
  .use('basic')
```

## Contributing
The [Senecajs org][] encourage open participation. If you feel you can help in any way, be it with
documentation, examples, extra testing, or new features please get in touch.

## Test
To run tests, simply use npm:

```
npm run test
```

## License
Copyright (c) 2016, Richard Rodger and other contributors.
Licensed under [MIT][].

[travis-badge]: https://travis-ci.org/senecajs/seneca-entity.svg
[travis-url]: https://travis-ci.org/senecajs/seneca-entity
[npm-badge]: https://badge.fury.io/js/seneca-entity.svg
[npm-url]: https://badge.fury.io/js/seneca-entity
[david-badge]: https://david-dm.org/senecajs/seneca-entity.svg
[david-url]: https://david-dm.org/senecajs/seneca-entity
[coveralls-badge]:https://coveralls.io/repos/senecajs/seneca-entity/badge.svg?branch=master&service=github
[coveralls-url]: https://coveralls.io/github/senecajs/seneca-entity?branch=master
[github issue]: https://github.com/senecajs/seneca-entity/issues
[@senecajs]: http://twitter.com/senecajs
[gitter-badge]: https://badges.gitter.im/Join%20Chat.svg
[gitter-url]: https://gitter.im/senecajs/seneca
[Senecajs org]: https://github.com/senecajs/
[Coveralls]: https://coveralls.io/github/senecajs/seneca-entity?branch=master
[BadgeCoveralls]: https://coveralls.io/repos/github/senecajs/seneca-entity/badge.svg?branch=master
[MIT]: ./LICENSE
