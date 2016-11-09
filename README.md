# node-class-export-example

An example for Stack Overflow answer:

* [How can I export a class in node?](https://stackoverflow.com/questions/40515954/how-can-i-export-a-class-in-node/40516570#40516570)

[github-url]: https://github.com/rsp/node-class-export-example
[readme-url]: https://github.com/rsp/node-class-export-example#readme
[issues-url]: https://github.com/rsp/node-class-export-example/issues
[license-url]: https://github.com/rsp/node-class-export-example/blob/master/LICENSE.md
[travis-url]: https://travis-ci.org/rsp/node-class-export-example
[travis-img]: https://travis-ci.org/rsp/node-class-export-example.svg?branch=master
[snyk-url]: https://snyk.io/test/github/rsp/node-class-export-example
[snyk-img]: https://snyk.io/test/github/rsp/node-class-export-example/badge.svg
[david-url]: https://david-dm.org/rsp/node-class-export-example
[david-img]: https://david-dm.org/rsp/node-class-export-example/status.svg
[install-img]: https://nodei.co/npm/errc.png?compact=true
[downloads-img]: https://img.shields.io/npm/dt/errc.svg
[license-img]: https://img.shields.io/npm/l/errc.svg
[stats-url]: http://npm-stat.com/charts.html?package=errc
[github-follow-url]: https://github.com/rsp
[github-follow-img]: https://img.shields.io/github/followers/rsp.svg?style=social&label=Follow
[twitter-follow-url]: https://twitter.com/intent/follow?screen_name=pocztarski
[twitter-follow-img]: https://img.shields.io/twitter/follow/pocztarski.svg?style=social&label=Follow
[stackoverflow-url]: https://stackoverflow.com/users/613198/rsp
[stackexchange-url]: https://stackexchange.com/users/303952/rsp
[stackexchange-img]: https://stackexchange.com/users/flair/303952.png
[travis-original-code-img]: https://api.travis-ci.org/rsp/node-class-export-example.svg?branch=original-code
[travis-original-code-img]: https://api.travis-ci.org/rsp/node-class-export-example.svg?branch=original-code
[travis-export-default-myclass-img]: https://api.travis-ci.org/rsp/node-class-export-example.svg?branch=export-default-myclass
[travis-module-exports-myclass-img]: https://api.travis-ci.org/rsp/node-class-export-example.svg?module-exports-myclass
[travis-branches-url]: https://travis-ci.org/rsp/node-class-export-example/branches
[branch-module-exports-myclass-url]: https://github.com/rsp/node-class-export-example/tree/module-exports-myclass
[branch-export-default-myclass-url]: https://github.com/rsp/node-class-export-example/tree/export-default-myclass
[branch-original-code-url]: https://github.com/rsp/node-class-export-example/tree/original-code

code.js
=
code.js:
```js
var MyClass = require('./class.js');
var myclass = new MyClass();
console.log('OK');
```

class.js
=
Original code
-
class.js:
```js
'use strict';
class MyClass {
}
module.exports = MyClass;
```
Tests: [![Build status][travis-original-code-img]][travis-branches-url]

original-code
-
Branch: [original-code][branch-original-code-url]

class.js:
```js
'use strict';
class MyClass {
}
module.exports = MyClass;
```
Tests: [![Build status][travis-original-code-img]][travis-branches-url]

module-exports-myclass
-
Branch: [module-exports-myclass][branch-module-exports-myclass-url]

class.js:
```js
'use strict';
class MyClass {
}
module.exports.MyClass = MyClass;
```
Tests: [![Build status][travis-module-exports-myclass-img]][travis-branches-url]

export-default-myclass
-
Branch: [export-default-myclass][branch-export-default-myclass-url]

class.js:
```js
'use strict';
class MyClass {
}
export default MyClass;
```
Tests: [![Build status][travis-export-default-myclass-img]][travis-branches-url]

Issues
------
For any bug reports or feature requests
please [post an issue on GitHub][issues-url].

Author
------
[**Rafał Pocztarski**](https://pocztarski.com/)
<br/>
[![Follow on GitHub][github-follow-img]][github-follow-url]
[![Follow on Twitter][twitter-follow-img]][twitter-follow-url]
<br/>
[![Follow on Stack Exchange][stackexchange-img]][stackoverflow-url]

License
-------
MIT License (Expat). See [LICENSE.md](LICENSE.md) for details.
