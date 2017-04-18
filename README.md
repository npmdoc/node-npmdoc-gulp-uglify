# npmdoc-gulp-uglify

#### api documentation for  [gulp-uglify (v2.1.2)](https://github.com/terinjokes/gulp-uglify/)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-uglify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-uglify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-uglify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-uglify)

#### Minify files with UglifyJS.

[![NPM](https://nodei.co/npm/gulp-uglify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-uglify)

- [https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-uglify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Terin Stock"
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
            "name": "terinjokes"
        }
    ],
    "name": "gulp-uglify",
    "optionalDependencies": {},
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
