# npmdoc-standard-format

#### api documentation for  [standard-format (v2.2.4)](https://github.com/maxogden/standard-format)  [![npm package](https://img.shields.io/npm/v/npmdoc-standard-format.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-standard-format) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-standard-format.svg)](https://travis-ci.org/npmdoc/node-npmdoc-standard-format)

#### attempts to reformat javascript to comply with feross/standard style

[![NPM](https://nodei.co/npm/standard-format.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/standard-format)

- [https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-standard-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-standard-format/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-standard-format/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "standard-format": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/standard-format/issues"
    },
    "dependencies": {
        "deglob": "^1.0.0",
        "esformatter": "^0.9.0",
        "esformatter-eol-last": "^1.0.0",
        "esformatter-jsx": "^7.0.0",
        "esformatter-literal-notation": "^1.0.0",
        "esformatter-quotes": "^1.0.0",
        "esformatter-remove-trailing-commas": "^1.0.1",
        "esformatter-semicolon-first": "^1.1.0",
        "esformatter-spaced-lined-comment": "^2.0.0",
        "minimist": "^1.1.0",
        "stdin": "0.0.1"
    },
    "description": "attempts to reformat javascript to comply with feross/standard style",
    "devDependencies": {
        "concat-stream": "^1.4.7",
        "debug": "^2.1.1",
        "once": "^1.3.1",
        "skip-stream": "0.0.3",
        "split": "^1.0.0",
        "standard": "*",
        "stream-reduce": "^1.0.3",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b90fb39a635f749cd4fd117fe4730d31179aaeef",
        "tarball": "https://registry.npmjs.org/standard-format/-/standard-format-2.2.4.tgz"
    },
    "gitHead": "a887dcc27e19afb378941703e4541db9eecaf56b",
    "homepage": "https://github.com/maxogden/standard-format",
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "maxogden"
        },
        {
            "name": "jb55"
        },
        {
            "name": "feross"
        },
        {
            "name": "bret"
        },
        {
            "name": "flet"
        }
    ],
    "name": "standard-format",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/standard-format.git"
    },
    "scripts": {
        "failing": "standard && tape test/failing/*.js | tap-spec",
        "test": "standard && tape test/*.js | tap-spec",
        "test-file": "<test/test-files/test.js ./bin.js | standard"
    },
    "standard": {
        "ignore": [
            "**test/test-files/**",
            "**test/failing/**"
        ]
    },
    "version": "2.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
