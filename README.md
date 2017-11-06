# [![module logo][module-logo-path]][module-logo-url]

[module-logo-path]: /resources/logo-sm.png

[module-logo-url]: /README.md

[![NPM version][npm-image]][npm-url] 
[![Dependency Status][daviddm-image]][daviddm-url] 
[![Donate](http://s-a.github.io/donate/donate.svg)](http://s-a.github.io/donate/)

> Plot serial chart data to an image and save it to filesystem from shell. Compatible with node 8.x

## Installation

```sh
$ npm install -g drawio
```

## Usage

```sh
$ type datafile.data | drawio --title measurement --width 2048
$ drawio --title measurement --inputfile tests.dat --outfile tests.png
```

## Demo

![Demo](/demo.gif)

## Parameter details and help

[COMMANDLINE-ARGUMENTS.md](COMMANDLINE-ARGUMENTS.md)

## License

MIT © [s-a](https://github.com/s-a)

[npm-image]: https://badge.fury.io/js/drawio.svg

[npm-url]: https://npmjs.org/package/drawio

[daviddm-image]: https://david-dm.org/s-a/drawio.svg?theme=shields.io

[daviddm-url]: https://david-dm.org/s-a/drawio
