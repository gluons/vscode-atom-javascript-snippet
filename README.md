# Atom JavaScript Snippet
[![license](https://img.shields.io/github/license/gluons/vscode-atom-javascript-snippet.svg?style=flat-square)](https://github.com/gluons/vscode-atom-javascript-snippet/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/gluons/vscode-atom-javascript-snippet.svg?style=flat-square)](https://github.com/gluons/vscode-atom-javascript-snippet/releases)

⚛ Atom JavaScript Snippet for Visual Studio Code 📄

The extension that provide [Atom](https://atom.io/) [JavaScript](https://github.com/atom/language-javascript) snippets for using in [Visual Studio Code](https://code.visualstudio.com/).

This snippet is based on [atom/language-javascript](https://github.com/atom/language-javascript/blob/master/snippets/language-javascript.cson).

## Snippets
### [`kf`] Object Method
```javascript
methodName: function (attribute) {
	
},
```

### [`kv`] Object key — key: "value"
```javascript
key: 'value', 
```

### [`proto`] Prototype
```javascript
ClassName.prototype.methodName = function () {
	
};
```

### [`do`] do
```javascript
do {
	
} while (true);
```

### [`if`] if
```javascript
if (true) {
	
}
```

### [`ife`] if … else
```javascript
if (true) {
	
} else {
	
}
```

### [`else`] else
```javascript
else {
	
}
```

### [`elseif`] else if
```javascript
else if (true) {
	
}
```

### [`for`] for
```javascript
for (var i = 0; i < array.length; i++) {
	array[i]
}
```

### [`forin`] for in
```javascript
for (var variable in object) {
	if (object.hasOwnProperty(variable)) {
		
	}
}
```

### [`forof`] for of
```javascript
for (variable of iterable) {
	
}
```

### [`fun`] Function
```javascript
function functionName() {
	
}
```

### [`f`] Anonymous Function
```javascript
function () {
	
}
```

### [`af`] Arrow Function
```javascript
() => {
	
}
```

### [`gen`] Generator
```javascript
function* functionName() {
	
}
```

### [`g`] Anonymous Generator
```javascript
function* () {
	
}
```

### [`get`] getElementsByClassName
```javascript
getElementsByClassName('className')
```

### [`getn`] getElementsByName
```javascript
getElementsByName('name')
```

### [`gett`] getElementsByTagName
```javascript
getElementsByTagName('tagName')
```

### [`geti`] getElementById
```javascript
getElementById('id')
```

### [`qs`] querySelector
```javascript
querySelector('query')
```

### [`qsa`] querySelectorAll
```javascript
querySelectorAll('query')
```

### [`iife`] Immediately-Invoked Function Expression
```javascript
(function() {
	'use strict';
	
}());
```
### [`log`] log
```javascript
console.log();
```

### [`warn`] warn
```javascript
console.warn();
```

### [`error`] error
```javascript
console.error();
```

### [`inspect`] inspect
```javascript
console.log(require('util').inspect(, { depth: null }));
```

### [`prom`] new Promise
```javascript
new Promise(function(resolve, reject) {
	
});
```

### [`interval`] setInterval function
```javascript
setInterval(function () {
	
}, 10);
```

### [`timeout`] setTimeout function
```javascript
setTimeout(function () {
	
}, 10);
```

### [`switch`] switch
```javascript
switch (expression) {
	case expression:
		
		break;
	default:
		
}
```

### [`case`] case
```javascript
case expression:
	
	break;
```

### [`try`] try
```javascript
try {
	
} catch (e) {
	
} finally {
	
}
```

### [`while`] while
```javascript
while (true) {
	
}
```

### [`/**`] Start Docblock
```javascript
/**
 * 
 */
```

### [`req`] CommonJS require
```javascript
const module = require('module');
```

### [`class`] Class
```javascript
class ClassName {
	constructor() {
		
	}
}
```

### [`expfun`] export function
```javascript
exports.functionName = function () {
	// body...
};
```

### [`expmod`] export module
```javascript
module.exports = name;
```
