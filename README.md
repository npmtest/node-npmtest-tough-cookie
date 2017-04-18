# npmtest-tough-cookie

#### test coverage for  [tough-cookie (v2.3.2)](https://github.com/salesforce/tough-cookie)  [![npm package](https://img.shields.io/npm/v/npmtest-tough-cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tough-cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tough-cookie.svg)](https://travis-ci.org/npmtest/node-npmtest-tough-cookie)

#### RFC6265 Cookies and Cookie Jar for node.js

[![NPM](https://nodei.co/npm/tough-cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tough-cookie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tough-cookie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tough-cookie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tough-cookie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tough-cookie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tough-cookie/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tough-cookie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tough-cookie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tough-cookie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tough-cookie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tough-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tough-cookie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tough-cookie/build/test-report.html](https://npmtest.github.io/node-npmtest-tough-cookie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tough-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tough-cookie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tough-cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tough-cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tough-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tough-cookie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tough-cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tough-cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Stashewsky"
    },
    "bugs": {
        "url": "https://github.com/salesforce/tough-cookie/issues"
    },
    "contributors": [
        {
            "name": "Alexander Savin"
        },
        {
            "name": "Ian Livingstone"
        },
        {
            "name": "Ivan Nikulin"
        },
        {
            "name": "Lalit Kapoor"
        },
        {
            "name": "Sam Thompson"
        },
        {
            "name": "Sebastian Mayr"
        }
    ],
    "dependencies": {
        "punycode": "^1.4.1"
    },
    "description": "RFC6265 Cookies and Cookie Jar for node.js",
    "devDependencies": {
        "async": "^1.4.2",
        "string.prototype.repeat": "^0.2.0",
        "vows": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f081f76e4c85720e6c37a5faced737150d84072a",
        "tarball": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.2.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "files": [
        "lib"
    ],
    "gitHead": "2610df5dc8ef7373a483d509006e5887572a4076",
    "homepage": "https://github.com/salesforce/tough-cookie",
    "keywords": [
        "HTTP",
        "cookie",
        "cookies",
        "set-cookie",
        "cookiejar",
        "jar",
        "RFC6265",
        "RFC2965"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/cookie",
    "maintainers": [
        {
            "name": "awaterma"
        },
        {
            "name": "jstash"
        },
        {
            "name": "nexxy"
        }
    ],
    "name": "tough-cookie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/salesforce/tough-cookie.git"
    },
    "scripts": {
        "suffixup": "curl -o public_suffix_list.dat https://publicsuffix.org/list/public_suffix_list.dat && ./generate-pubsuffix.js",
        "test": "vows test/*_test.js"
    },
    "version": "2.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
