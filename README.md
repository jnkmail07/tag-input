# Tag-Input (with React)

[![SemVer]](http://semver.org)
[![License]](https://github.com/tjunghans/tag-input/blob/master/LICENCE)
[![Build Status](https://travis-ci.org/tjunghans/tag-input.svg?branch=master)](https://travis-ci.org/tjunghans/tag-input)

A react component that renders an input field. When hitting enter or entering a comma, the value will be used to create a tag. Tags are displayed in front of the input.

[Demo](http://tangiblej.neocities.org/tag-input-example.html)


## Install

Install as node dependency:

```
npm install tag-input --save
```


## Quickstart

To test locally change to node_modules/tag-input and run:

```
npm start & npm run watch
```


## Commands

- `npm run build` - build production css and js
- `npm run watch` - compile css and js
- `npm run watch:test` - run tests on change
- `npm start` - start static dev server
- `npm test` - run lint and tests


## Usage

```javascript
var React = require('react');
var tagInput = require('tag-input');

React.render(React.createElement(tagInput),
  document.querySelector('#content'));
```


## Component Props

- `onTagChange`: called when a tag is added or removed. Called with tags array.
- `cssClass`: optional css class for container


## License

MIT

[SemVer]: http://img.shields.io/:semver-%E2%9C%93-brightgreen.svg
[License]: http://img.shields.io/npm/l/mochify.svg


