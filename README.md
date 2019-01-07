# @sarath_subramaniam/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sarath_subramaniam/tiny.svg)](https://www.npmjs.com/package/@sarath_subramaniam/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sarath_subramaniam/tiny.svg)](https://www.npmjs.com/package/@sarath_subramaniam/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sarath_subramaniam/tiny
```

## Usage

```js
const tiny = require("@sarath_subramaniam/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```