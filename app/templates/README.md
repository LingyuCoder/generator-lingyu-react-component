# <%= name %>

[![Test coverage](https://img.shields.io/coveralls/<%= author %>/<%= name %>.svg?style=flat-square)](https://coveralls.io/r/<%= author %>/<%= name %>?branch=master)
[![Build Status](https://travis-ci.org/<%= author %>/<%= name %>.png)](https://travis-ci.org/<%= author %>/<%= name %>)
[![Dependency Status](https://david-dm.org/<%= author %>/<%= name %>.svg)](https://david-dm.org/<%= author %>/<%= name %>)
[![devDependency Status](https://david-dm.org/<%= author %>/<%= name %>/dev-status.svg)](https://david-dm.org/<%= author %>/<%= name %>#info=devDependencies)
[![NPM version](http://img.shields.io/npm/v/<%= name %>.svg?style=flat-square)](http://npmjs.org/package/<%= name %>)
[![node](https://img.shields.io/badge/node.js-%3E=_4.0-green.svg?style=flat-square)](http://nodejs.org/download/)
[![License](http://img.shields.io/npm/l/<%= name %>.svg?style=flat-square)](LICENSE)
[![npm download](https://img.shields.io/npm/dm/<%= name %>.svg?style=flat-square)](https://npmjs.org/package/<%= name %>)

> <%= description %>

## Demo

[Demo here](http://<%= author %>.github.io/<%= name %>/demo/index.html)

## Installation

```bash
$ npm install --save <%= name %>
```

## Usage

```javascript
import <%= component %> from '<%= name %>';
<<%= component %> />;
```

## Properties

[insert]: # (start:src/index.jsx|doc)
| Name | Description | Type | Required | Default Value |
| :--- | :----- | :--- | :---: | :---: |
| content | content of element | String |  | `'Hello world'` |
[insert]: # (end:src/index.jsx)

## Development

[Online test page here](http://<%= author %>.github.io/<%= name %>/test/test.html)

```bash
$ npm run dev # startup local dev server
$ npm run build # build
$ npm run test # run tests
$ npm run cov # run coverage
$ npm run build-demo # build demo, auto run in 'npm run build'
$ npm run build-test # build test, auto run in 'npm run build'
```

## License

The MIT License (MIT)

Copyright (c) 2015 <%= author %>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
