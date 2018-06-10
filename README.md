# npmtest-request

#### basic test coverage for  [request (2.87.0)](https://github.com/request/request#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-request.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request.svg)](https://travis-ci.org/npmtest/node-npmtest-request)

#### Simplified HTTP request client.

[![NPM](https://nodei.co/npm/request.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-request/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-request/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-request/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-request/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request/build/test-report.html](https://npmtest.github.io/node-npmtest-request/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request/build/screenshot.npmPackageDependencyTree.svg)



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
        "aws-sign2": "~0.7.0",
        "aws4": "^1.6.0",
        "caseless": "~0.12.0",
        "combined-stream": "~1.0.5",
        "extend": "~3.0.1",
        "forever-agent": "~0.6.1",
        "form-data": "~2.3.1",
        "har-validator": "~5.0.3",
        "http-signature": "~1.2.0",
        "is-typedarray": "~1.0.0",
        "isstream": "~0.1.2",
        "json-stringify-safe": "~5.0.1",
        "mime-types": "~2.1.17",
        "oauth-sign": "~0.8.2",
        "performance-now": "^2.1.0",
        "qs": "~6.5.1",
        "safe-buffer": "^5.1.1",
        "tough-cookie": "~2.3.3",
        "tunnel-agent": "^0.6.0",
        "uuid": "^3.1.0"
    },
    "description": "Simplified HTTP request client.",
    "devDependencies": {
        "bluebird": "^3.2.1",
        "browserify": "^13.0.1",
        "browserify-istanbul": "^2.0.0",
        "buffer-equal": "^1.0.0",
        "codecov": "^2.0.2",
        "coveralls": "^2.11.4",
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
        "standard": "^9.0.0",
        "tape": "^4.6.0",
        "taper": "^0.5.0"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-fcogkm7Az5bsS6Sl0sibkbhcKsnyon/jV1kF3ajGmF0c8HrttdKTPRT9hieOaQHA5HEq6r8OyWOo/o781C1tNw==",
        "shasum": "32f00235cd08d482b4d0d68db93a829c0ed5756e",
        "tarball": "https://registry.npmjs.org/request/-/request-2.87.0.tgz",
        "fileCount": 17,
        "unpackedSize": 206652,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJbAnapCRA9TVsSAnZWagAAn44P/3RyMkTB2JOuitF4Ar5t\nkc2Ma4HuCxaiFpI/2sXHN/kzYm1Vsv0W4PGeyIxPqnKu99zbUGdVPi27lfDU\nmWADUxX0ujUH5L/BoivUi/sMGvroKGMrwhO2DZlVHdfl6y6dMLyqQ7XLT7EH\nu5VJCGbmBnWfrL3ZjvHoIXOW7byAXHXoNBD85cX3s4J+wOQ7ZiWoCjfM9/9G\nSbQPYO+Ji5UNT6706DTh+doBuI9fXsdugh/9gPMGvpm9leYQ2r8KRAisuENj\nZvYwBcTq8PPtdHvwT6dKIe/HYm6IwI+f3U7rVcHjHvwb4a9RmU5jPmIqwM5v\nEj5GqFq18aoRsQkv0ktOnGBMBoklx867F2rdQZjXd+GrMzbWBAQjYpFui/pK\nlWLRz5G4FL8O7wYbGHgXYOwfkP1am5guF6FOvfq2i5ajK6gIz5JG9Ln0RUYk\nKVqfMGYWbKvt1UQCaAHqjfyq1TvMS1rrouQeJtmhbf3RqAXecw1LbZsA6SxT\n+EmP28zEcmJuuo77v6y06g4XZZ1snmGnlEx4NfweGuMtRJmTGo/mUO7aGLmx\nK2oNJGLf2TJpTPSnmysglUirr5D0RZ/mmvfmrWqxWsD+Jyngks0gD47BjCcZ\nrmUcaFslqAcNV2iY2mASr8Dts/vZfchcUSxCkHhAN7As4EsBv07ziDVlS2AR\n/gk2\r\n=6VhQ\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "engines": {
        "node": ">= 4"
    },
    "files": [
        "lib/",
        "index.js",
        "request.js"
    ],
    "gitHead": "02fc5b1f0123173c308a79c43e804f6fcbefbbaf",
    "greenkeeper": {
        "ignore": [
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
            "name": "fredkschott"
        },
        {
            "name": "mikeal"
        },
        {
            "name": "nylen"
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
        "lint": "standard",
        "test": "npm run lint && npm run test-ci && npm run test-browser",
        "test-browser": "node tests/browser/start.js",
        "test-ci": "taper tests/test-*.js",
        "test-cov": "istanbul cover tape tests/test-*.js"
    },
    "version": "2.87.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
