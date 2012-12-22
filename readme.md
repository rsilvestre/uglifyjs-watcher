About
=====

Tired of minifiying your JS files manually? You can use uglifyjs-watcher to watch your changes in js files. Uglifyjs-watcher will minify all your files whenever you save your files.

Installation
============

```html
npm install uglifyjs-watcher -g
```

JSON Format
========================================

```javascript
{

	"uglify-js-arguments": "-o",
	"scripts": [
	],

	"minifiedFilename": "minified.js"

}
```

Syntax
======

```html
uglifyjs-watcher minify.json
```
