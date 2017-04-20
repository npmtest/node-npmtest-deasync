# npmtest-deasync

#### basic test coverage for  [deasync (v0.1.9)](https://github.com/abbr/deasync)  [![npm package](https://img.shields.io/npm/v/npmtest-deasync.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-deasync) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-deasync.svg)](https://travis-ci.org/npmtest/node-npmtest-deasync)

#### Turns async function into sync via JavaScript wrapper of Node event loop

[![NPM](https://nodei.co/npm/deasync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deasync)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-deasync/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-deasync/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-deasync/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-deasync/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-deasync/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-deasync/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-deasync/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-deasync/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-deasync/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-deasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-deasync/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-deasync/build/test-report.html](https://npmtest.github.io/node-npmtest-deasync/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-deasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-deasync/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-deasync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deasync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deasync/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-deasync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-deasync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "deasync",
    "version": "0.1.9",
    "description": "Turns async function into sync via JavaScript wrapper of Node event loop",
    "main": "index.js",
    "author": "Vladimir Kurchatkin <vladimir.kurchatkin@gmail.com>",
    "contributors": [
        "Fred Wen <wenfred@gmail.com> (https://github.com/abbr)"
    ],
    "license": "MIT",
    "scripts": {
        "install": "node ./build.js"
    },
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.0.7"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/abbr/deasync.git"
    },
    "homepage": "https://github.com/abbr/deasync",
    "keywords": [
        "async",
        "sync",
        "sleep",
        "async wrapper"
    ],
    "engines": {
        "node": ">=0.11.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
