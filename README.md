[![Build Status](https://travis-ci.org/dferber90/Paw-httpstatCodeGenerator.svg?branch=master)](https://travis-ci.org/dferber90/Paw-httpstatCodeGenerator)

# httpstat Code Generator (Paw Extension)

A [Paw Extension](https://paw.cloud/extensions/) that generates [httpstat](https://github.com/davecheney/httpstat) command line code.

## Installation

Easily install this Paw Extension: [Install httpstat Code Generator](https://paw.cloud/extensions/HttpStatCodeGenerator)

## Development

### Build & Install

```shell
npm install
npm run cake build
npm run cake install
```

### Watch

During development, watch for changes:

```shell
npm run cake watch
```


## License

This Paw Extension is released under the [MIT License](LICENSE). Feel free to fork, and modify!

## Contributors

See [Contributors](https://github.com/luckymarmot/Paw-cURLCodeGenerator/graphs/contributors).

## Credits

This repo is a fork of [cURLCodeGenerator](https://github.com/luckymarmot/Paw-cURLCodeGenerator) with slight modifications to output `httpstat` instead of `curl` code.

The other major difference is that `httpstat` requires the URL as the first argument while `curl` is more flexible. So this package will always emit the URL as the first argument, where as `cURLCodeGenerator` does not.

* [cURLCodeGenerator](https://github.com/luckymarmot/Paw-cURLCodeGenerator), also released under the MIT License
* [Mustache.js](https://github.com/janl/mustache.js/), also released under the MIT License
* [URI.js](http://medialize.github.io/URI.js/), also released under the MIT License
