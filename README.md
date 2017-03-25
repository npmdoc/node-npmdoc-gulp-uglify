# api documentation for  [gulp-uglify (v2.1.2)](https://github.com/terinjokes/gulp-uglify/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-uglify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-uglify)
#### Minify files with UglifyJS.

[![NPM](https://nodei.co/npm/gulp-uglify.png?downloads=true)](https://www.npmjs.com/package/gulp-uglify)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp_uglify_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Terin Stock",
        "email": "terinjokes@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/terinjokes/gulp-uglify/issues"
    },
    "dependencies": {
        "gulplog": "^1.0.0",
        "has-gulplog": "^0.1.0",
        "lodash": "^4.13.1",
        "make-error-cause": "^1.1.1",
        "through2": "^2.0.0",
        "uglify-js": "~2.8.10",
        "uglify-save-license": "^0.4.1",
        "vinyl-sourcemaps-apply": "^0.2.0"
    },
    "description": "Minify files with UglifyJS.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "eslint": "^3.18.0",
        "eslint-config-prettier": "^1.5.0",
        "eslint-config-xo": "^0.18.1",
        "eslint-plugin-no-use-extend-native": "^0.3.12",
        "eslint-plugin-prettier": "^2.0.1",
        "eslint-plugin-unicorn": "^2.1.0",
        "gulp-concat": "^2.0.0",
        "gulp-sourcemaps": "^1.0.0",
        "intelli-espower-loader": "^1.0.1",
        "istanbul": "^0.4.0",
        "mississippi": "^1.2.0",
        "mocha": "^3.0.1",
        "power-assert": "^1.4.1",
        "prettier": "^0.22.0",
        "semver": "^5.3.0",
        "tape": "^4.0.0",
        "testdouble": "^1.6.0",
        "vinyl": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6db85b1d0ee63d18058592b658649d65c2ec4541",
        "tarball": "https://registry.npmjs.org/gulp-uglify/-/gulp-uglify-2.1.2.tgz"
    },
    "eslintConfig": {
        "env": {
            "node": true
        },
        "extends": [
            "xo",
            "prettier"
        ],
        "plugins": [
            "unicorn",
            "no-use-extend-native",
            "prettier"
        ],
        "rules": {
            "prettier/prettier": [
                "error",
                {
                    "printWidth": 80,
                    "tabWidth": 2,
                    "singleQuote": true,
                    "trailingComma": "none",
                    "bracketSpacing": false
                }
            ]
        }
    },
    "files": [
        "index.js",
        "minifier.js",
        "lib/"
    ],
    "gitHead": "4656fe56c8b288091c7704c5955ff5170ec3ba74",
    "greenkeeper": {
        "ignore": [
            "gulp-sourcemaps"
        ]
    },
    "homepage": "https://github.com/terinjokes/gulp-uglify/",
    "keywords": [
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "terinjokes",
            "email": "terinjokes@gmail.com"
        }
    ],
    "name": "gulp-uglify",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/terinjokes/gulp-uglify.git"
    },
    "scripts": {
        "coverage": "cat ./coverage/lcov.info | coveralls",
        "lint": "eslint *.js lib test",
        "test": "mocha --require intelli-espower-loader"
    },
    "version": "2.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-uglify](#apidoc.module.gulp-uglify)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError ()](#apidoc.element.gulp-uglify.GulpUglifyError)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError.super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super)
1.  object <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError.prototype
1.  object <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError.super.prototype
1.  object <span class="apidocSignatureSpan">gulp-uglify.</span>log

#### [module gulp-uglify.GulpUglifyError](#apidoc.module.gulp-uglify.GulpUglifyError)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError ()](#apidoc.element.gulp-uglify.GulpUglifyError.GulpUglifyError)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super_ (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super_)

#### [module gulp-uglify.GulpUglifyError.prototype](#apidoc.module.gulp-uglify.GulpUglifyError.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.prototype.</span>toString ()](#apidoc.element.gulp-uglify.GulpUglifyError.prototype.toString)

#### [module gulp-uglify.GulpUglifyError.super](#apidoc.module.gulp-uglify.GulpUglifyError.super)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super.super)

#### [module gulp-uglify.GulpUglifyError.super.prototype](#apidoc.module.gulp-uglify.GulpUglifyError.super.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.super.prototype.</span>constructor (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.super.prototype.</span>toString ()](#apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.toString)

#### [module gulp-uglify.log](#apidoc.module.gulp-uglify.log)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.log.</span>debug ()](#apidoc.element.gulp-uglify.log.debug)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.log.</span>error ()](#apidoc.element.gulp-uglify.log.error)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.log.</span>info ()](#apidoc.element.gulp-uglify.log.info)
1.  [function <span class="apidocSignatureSpan">gulp-uglify.log.</span>warn ()](#apidoc.element.gulp-uglify.log.warn)



# <a name="apidoc.module.gulp-uglify"></a>[module gulp-uglify](#apidoc.module.gulp-uglify)

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError"></a>[function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError ()](#apidoc.element.gulp-uglify.GulpUglifyError)
- description and source-code
```javascript
GulpUglifyError = function () { super_.apply(this, arguments) }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super"></a>[function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError.super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super)
- description and source-code
```javascript
function BaseError(message, cause) {
    _super.call(this, message);
    this.cause = cause;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-uglify.GulpUglifyError"></a>[module gulp-uglify.GulpUglifyError](#apidoc.module.gulp-uglify.GulpUglifyError)

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.GulpUglifyError"></a>[function <span class="apidocSignatureSpan">gulp-uglify.</span>GulpUglifyError ()](#apidoc.element.gulp-uglify.GulpUglifyError.GulpUglifyError)
- description and source-code
```javascript
GulpUglifyError = function () { super_.apply(this, arguments) }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super)
- description and source-code
```javascript
function BaseError(message, cause) {
    _super.call(this, message);
    this.cause = cause;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super_"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super_ (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super_)
- description and source-code
```javascript
function BaseError(message, cause) {
    _super.call(this, message);
    this.cause = cause;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-uglify.GulpUglifyError.prototype"></a>[module gulp-uglify.GulpUglifyError.prototype](#apidoc.module.gulp-uglify.GulpUglifyError.prototype)

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.prototype.toString"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.prototype.</span>toString ()](#apidoc.element.gulp-uglify.GulpUglifyError.prototype.toString)
- description and source-code
```javascript
toString = function () {
  var cause = this.cause || {};

  return makeErrorCause.BaseError.prototype.toString.call(this) +
    (this.fileName ? '\nFile: ' + this.fileName : '') +
    (cause.line ? '\nLine: ' + cause.line : '');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-uglify.GulpUglifyError.super"></a>[module gulp-uglify.GulpUglifyError.super](#apidoc.module.gulp-uglify.GulpUglifyError.super)

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super.super"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.</span>super (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super.super)
- description and source-code
```javascript
function BaseError(message, cause) {
    _super.call(this, message);
    this.cause = cause;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-uglify.GulpUglifyError.super.prototype"></a>[module gulp-uglify.GulpUglifyError.super.prototype](#apidoc.module.gulp-uglify.GulpUglifyError.super.prototype)

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.super.prototype.</span>constructor (message, cause)](#apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.constructor)
- description and source-code
```javascript
function BaseError(message, cause) {
    _super.call(this, message);
    this.cause = cause;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.toString"></a>[function <span class="apidocSignatureSpan">gulp-uglify.GulpUglifyError.super.prototype.</span>toString ()](#apidoc.element.gulp-uglify.GulpUglifyError.super.prototype.toString)
- description and source-code
```javascript
toString = function () {
    return _super.prototype.toString.call(this) + (this.cause ? "\nCaused by: " + this.cause.toString() : '');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-uglify.log"></a>[module gulp-uglify.log](#apidoc.module.gulp-uglify.log)

#### <a name="apidoc.element.gulp-uglify.log.debug"></a>[function <span class="apidocSignatureSpan">gulp-uglify.log.</span>debug ()](#apidoc.element.gulp-uglify.log.debug)
- description and source-code
```javascript
debug = function () {
  if (hasLog()) {
    var log = require('gulplog');

    log[level].apply(log, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.log.error"></a>[function <span class="apidocSignatureSpan">gulp-uglify.log.</span>error ()](#apidoc.element.gulp-uglify.log.error)
- description and source-code
```javascript
error = function () {
  if (hasLog()) {
    var log = require('gulplog');

    log[level].apply(log, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.log.info"></a>[function <span class="apidocSignatureSpan">gulp-uglify.log.</span>info ()](#apidoc.element.gulp-uglify.log.info)
- description and source-code
```javascript
info = function () {
  if (hasLog()) {
    var log = require('gulplog');

    log[level].apply(log, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-uglify.log.warn"></a>[function <span class="apidocSignatureSpan">gulp-uglify.log.</span>warn ()](#apidoc.element.gulp-uglify.log.warn)
- description and source-code
```javascript
warn = function () {
  if (hasLog()) {
    var log = require('gulplog');

    log[level].apply(log, arguments);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
