# npmdoc-indicative

#### basic api documentation for  [indicative (v2.2.1)](https://github.com/poppinss/indicative#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-indicative.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-indicative) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-indicative.svg)](https://travis-ci.org/npmdoc/node-npmdoc-indicative)

#### Intentionally beautiful schema and raw validator for nodejs

[![NPM](https://nodei.co/npm/indicative.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/indicative)

- [https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-indicative/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-indicative/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-indicative/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "amanvirk"
    },
    "bugs": {
        "url": "https://github.com/poppinss/indicative/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "inflect": "^0.3.0",
        "lodash": "^4.12.0",
        "moment": "^2.13.0",
        "pope": "^1.0.0",
        "q": "^2.0.3"
    },
    "description": "Intentionally beautiful schema and raw validator for nodejs",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "chai": "^3.5.0",
        "co-mocha": "^1.1.2",
        "coveralls": "^2.11.9",
        "cz-conventional-changelog": "^1.1.6",
        "istanbul": "^0.4.3",
        "mocha": "^3.0.2",
        "mocha-lcov-reporter": "^1.2.0",
        "standard": "^8.4.0"
    },
    "directories": {
        "doc": "docs",
        "test": "test"
    },
    "dist": {
        "shasum": "2d007aef269c0ca6bf136c5577f0ace4361fb4de",
        "tarball": "https://registry.npmjs.org/indicative/-/indicative-2.2.1.tgz"
    },
    "gitHead": "ac6af436864163c428b717072f6190c46220f9f0",
    "homepage": "https://github.com/poppinss/indicative#readme",
    "keywords": [
        "node-validator",
        "validator",
        "schema-validator",
        "quick-validations"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "adonisjs"
        },
        {
            "name": "amanvirk"
        }
    ],
    "name": "indicative",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/poppinss/indicative.git"
    },
    "scripts": {
        "coverage": "npm run lint && istanbul cover _mocha test --bail",
        "lint": "standard",
        "test": "npm run lint && istanbul cover _mocha --report lcovonly -- -R spec test && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    },
    "standard": {
        "global": [
            "it",
            "describe",
            "context",
            "before",
            "after",
            "beforeEach",
            "afterEach"
        ]
    },
    "version": "2.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
