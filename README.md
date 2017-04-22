# npmtest-pickup

#### basic test coverage for  [pickup (v5.1.1)](https://github.com/michaelnisi/pickup)  [![npm package](https://img.shields.io/npm/v/npmtest-pickup.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pickup) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pickup.svg)](https://travis-ci.org/npmtest/node-npmtest-pickup)

#### Transform RSS or Atom XML to JSON

[![NPM](https://nodei.co/npm/pickup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pickup)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pickup/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pickup/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pickup/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pickup/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pickup/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pickup/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pickup/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pickup/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pickup/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pickup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pickup/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pickup/build/test-report.html](https://npmtest.github.io/node-npmtest-pickup/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pickup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pickup/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pickup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pickup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pickup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pickup",
    "version": "5.1.1",
    "description": "Transform RSS or Atom XML to JSON",
    "main": "index.js",
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "pretest": "standard",
        "test": "tap test/*.js --cov"
    },
    "bin": {
        "pickup": "bin/cli.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/michaelnisi/pickup.git"
    },
    "keywords": [
        "rss",
        "atom",
        "xml",
        "json",
        "itunes",
        "podcast",
        "feed",
        "transform",
        "stream",
        "through",
        "streams2"
    ],
    "bugs": {
        "url": "https://github.com/michaelnisi/pickup/issues"
    },
    "homepage": "https://github.com/michaelnisi/pickup",
    "dependencies": {
        "readable-stream": "^2.1.5",
        "sax": "^1.2.1"
    },
    "devDependencies": {
        "standard": "^8.5.0",
        "tap": "^8.0.0"
    },
    "engines": {
        "node": ">=4"
    },
    "author": "Michael Nisi <michael.nisi@gmail.com> (http://troubled.pro)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
