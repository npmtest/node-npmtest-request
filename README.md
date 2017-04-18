# npmtest-request

#### test coverage for  [request (v2.81.0)](https://github.com/request/request#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-request.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request.svg)](https://travis-ci.org/npmtest/node-npmtest-request)

#### Simplified HTTP request client.

[![NPM](https://nodei.co/npm/request.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-request/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request/build/test-report.html](https://npmtest.github.io/node-npmtest-request/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikeal Rogers"
    },
    "bugs": {
        "url": "http://github.com/request/request/issues"
    },
    "dependencies": {
        "aws-sign2": "~0.6.0",
        "aws4": "^1.2.1",
        "caseless": "~0.12.0",
        "combined-stream": "~1.0.5",
        "extend": "~3.0.0",
        "forever-agent": "~0.6.1",
        "form-data": "~2.1.1",
        "har-validator": "~4.2.1",
        "hawk": "~3.1.3",
        "http-signature": "~1.1.0",
        "is-typedarray": "~1.0.0",
        "isstream": "~0.1.2",
        "json-stringify-safe": "~5.0.1",
        "mime-types": "~2.1.7",
        "oauth-sign": "~0.8.1",
        "performance-now": "^0.2.0",
        "qs": "~6.4.0",
        "safe-buffer": "^5.0.1",
        "stringstream": "~0.0.4",
        "tough-cookie": "~2.3.0",
        "tunnel-agent": "^0.6.0",
        "uuid": "^3.0.0"
    },
    "description": "Simplified HTTP request client.",
    "devDependencies": {
        "bluebird": "^3.2.1",
        "browserify": "^13.0.1",
        "browserify-istanbul": "^2.0.0",
        "buffer-equal": "^1.0.0",
        "codecov": "^1.0.1",
        "coveralls": "^2.11.4",
        "eslint": "^2.5.3",
        "function-bind": "^1.0.2",
        "istanbul": "^0.4.0",
        "karma": "^1.1.1",
        "karma-browserify": "^5.0.1",
        "karma-cli": "^1.0.0",
        "karma-coverage": "^1.0.0",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-tap": "^3.0.1",
        "phantomjs-prebuilt": "^2.1.3",
        "rimraf": "^2.2.8",
        "server-destroy": "^1.0.1",
        "tape": "^4.6.0",
        "taper": "^0.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c6928946a0e06c5f8d6f8a9333469ffda46298a0",
        "tarball": "https://registry.npmjs.org/request/-/request-2.81.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "files": [
        "lib/",
        "index.js",
        "request.js"
    ],
    "gitHead": "a0cdc704c19e63e6f1740e173bb003c51eef524c",
    "greenkeeper": {
        "ignore": [
            "eslint",
            "hawk",
            "har-validator"
        ]
    },
    "homepage": "https://github.com/request/request#readme",
    "keywords": [
        "http",
        "simple",
        "util",
        "utility"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mikeal"
        },
        {
            "name": "nylen"
        },
        {
            "name": "fredkschott"
        },
        {
            "name": "simov"
        }
    ],
    "name": "request",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/request/request.git"
    },
    "scripts": {
        "lint": "eslint lib/ *.js tests/ && echo Lint passed.",
        "test": "npm run lint && npm run test-ci && npm run test-browser",
        "test-browser": "node tests/browser/start.js",
        "test-ci": "taper tests/test-*.js",
        "test-cov": "istanbul cover tape tests/test-*.js"
    },
    "version": "2.81.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
