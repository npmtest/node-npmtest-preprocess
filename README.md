# npmtest-preprocess

#### basic test coverage for  [preprocess (v3.1.0)](https://github.com/jsoverson/preprocess)  [![npm package](https://img.shields.io/npm/v/npmtest-preprocess.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-preprocess) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-preprocess.svg)](https://travis-ci.org/npmtest/node-npmtest-preprocess)

#### Preprocess directives in HTML, JavaScript, etc directives based off variable context

[![NPM](https://nodei.co/npm/preprocess.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/preprocess)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-preprocess/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-preprocess/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-preprocess/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-preprocess/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-preprocess/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-preprocess/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-preprocess/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-preprocess/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-preprocess/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-preprocess/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-preprocess/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-preprocess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-preprocess/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-preprocess/build/test-report.html](https://npmtest.github.io/node-npmtest-preprocess/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-preprocess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-preprocess/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-preprocess/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-preprocess/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-preprocess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-preprocess/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-preprocess/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-preprocess/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jarrod Overson",
        "url": "http://jarrodoverson.com/"
    },
    "bugs": {
        "url": "https://github.com/jsoverson/preprocess/issues"
    },
    "dependencies": {
        "xregexp": "3.1.0"
    },
    "description": "Preprocess directives in HTML, JavaScript, etc directives based off variable context",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-spies": "^0.7.0",
        "grunt": "^0.4.5",
        "grunt-benchmark": "^0.3.0",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^0.8.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-coveralls": "^1.0.0",
        "grunt-deps-ok": "^0.9.0",
        "grunt-mocha-istanbul": "^3.0.1",
        "grunt-mocha-test": "^0.12.7",
        "istanbul": "^0.4.2",
        "load-grunt-tasks": "^3.4.0",
        "mocha": "^2.4.5",
        "time-grunt": "^1.3.0",
        "travis-cov": "^0.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "a44e5cdd5bbb5a54f0ad289aaeed80995d7d938a",
        "tarball": "https://registry.npmjs.org/preprocess/-/preprocess-3.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "a5ddda7fa80917ce04076616bfafe5837f3cf11c",
    "homepage": "https://github.com/jsoverson/preprocess",
    "keywords": [
        "directive",
        "ENV",
        "environment",
        "ifdef",
        "ifndef",
        "echo",
        "include",
        "exclude",
        "process",
        "preprocess",
        "pragma"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "https://github.com/jsoverson/preprocess/blob/master/LICENSE"
        }
    ],
    "main": "lib/preprocess.js",
    "maintainers": [
        {
            "name": "jsoverson"
        },
        {
            "name": "bendingbender"
        }
    ],
    "name": "preprocess",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jsoverson/preprocess.git"
    },
    "scripts": {
        "ci": "grunt ci",
        "test": "grunt test"
    },
    "version": "3.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
