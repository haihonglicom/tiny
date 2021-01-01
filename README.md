# @haihongli/tiny

Removes all spaces from a string.

## Install

```
$ npm install @haihongli/tiny
```

## Usage

```
const tiny = require('@haihongli/tiny')

tiny('So much space!')
//=> Somuchspace!

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
```
