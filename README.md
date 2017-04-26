# npmtest-bignumber.js

#### basic test coverage for  [bignumber.js (v4.0.1)](https://github.com/MikeMcl/bignumber.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bignumber.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bignumber.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bignumber.js.svg)](https://travis-ci.org/npmtest/node-npmtest-bignumber.js)

#### A library for arbitrary-precision decimal and non-decimal arithmetic

[![NPM](https://nodei.co/npm/bignumber.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bignumber.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bignumber.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bignumber.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bignumber.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bignumber.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bignumber.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bignumber.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bignumber.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bignumber.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bignumber.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bignumber.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bignumber.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bignumber.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bignumber.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bignumber.js/build/test-report.html](https://npmtest.github.io/node-npmtest-bignumber.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bignumber.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bignumber.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bignumber.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bignumber.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bignumber.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bignumber.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bignumber.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bignumber.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Mclaughlin"
    },
    "bugs": {
        "url": "https://github.com/MikeMcl/bignumber.js/issues"
    },
    "dependencies": {},
    "description": "A library for arbitrary-precision decimal and non-decimal arithmetic",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "1ffd30d349366e078bd6f7dc97907e6da9a71888",
        "tarball": "https://registry.npmjs.org/bignumber.js/-/bignumber.js-4.0.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "b2ed4a015a49ccb9532dfccf73a7b3d918bde6f7",
    "homepage": "https://github.com/MikeMcl/bignumber.js#readme",
    "keywords": [
        "arbitrary",
        "precision",
        "arithmetic",
        "big",
        "number",
        "decimal",
        "float",
        "biginteger",
        "bigdecimal",
        "bignumber",
        "bigint",
        "bignum"
    ],
    "license": "MIT",
    "main": "bignumber.js",
    "maintainers": [
        {
            "name": "mikemcl"
        }
    ],
    "name": "bignumber.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MikeMcl/bignumber.js.git"
    },
    "scripts": {
        "build": "uglifyjs bignumber.js --source-map bignumber.js.map -c -m -o bignumber.min.js --preamble \"/* bignumber.js v4.0.1 https://github.com/MikeMcl/bignumber.js/LICENCE */\"",
        "test": "node ./test/every-test.js"
    },
    "version": "4.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
