# focusin

[![npm][npm-image]][npm-url]

> Focusin/focusout polyfill for Firefox based on [this gist](https://gist.github.com/nuxodin/9250e56a3ce6c0446efa) by [@nuxodin](https://github.com/nuxodin). Addresses [this bug](https://bugzilla.mozilla.org/show_bug.cgi?id=687787) in Firefox.

## Install

```
npm install focusin
```

Or, just copy `focusin.min.js` into your project if you don't use browserify.

## Usage

focusin is a polyfill, so you don't need to assign it to a variable, just require it. Obviously meant for browser environments and not Node.js.

```js
require('focusin')();
```

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

[ISC](LICENSE.md)

Project template generated with [module-init](https://www.npmjs.com/package/module-init).

[npm-image]: https://img.shields.io/npm/v/focusin.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/focusin
