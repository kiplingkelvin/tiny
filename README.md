# @kipling/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@kipling/tiny.svg)](https://www.npmjs.com/package/@kipling/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@kipling/tiny.svg)](https://www.npmjs.com/package/@kipling/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @kipling/tiny
```

## Usage

```js
const tiny = require("@kipling/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
