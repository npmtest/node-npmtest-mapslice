# npmtest-mapslice

#### basic test coverage for  [mapslice (v1.3.0)](https://github.com/martinheidegger/mapslice)  [![npm package](https://img.shields.io/npm/v/npmtest-mapslice.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mapslice) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mapslice.svg)](https://travis-ci.org/npmtest/node-npmtest-mapslice)

#### Slices a given image into tiles to be used for a interactive map display. (including command-line tool)

[![NPM](https://nodei.co/npm/mapslice.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mapslice)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mapslice/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mapslice/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mapslice/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mapslice/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mapslice/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mapslice/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mapslice/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mapslice/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mapslice/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mapslice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mapslice/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mapslice/build/test-report.html](https://npmtest.github.io/node-npmtest-mapslice/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mapslice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mapslice/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mapslice/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mapslice/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mapslice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mapslice/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mapslice/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mapslice/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martin Heidegger"
    },
    "bin": {
        "mapslice": "./bin/mapslice"
    },
    "bugs": {
        "url": "https://github.com/martinheidegger/mapslice/issues"
    },
    "contributors": [
        {
            "name": "Aaron Blondeau",
            "url": "https://github.com/aaronblondeau"
        },
        {
            "name": "F. Orlando",
            "url": "https://github.com/frulo"
        }
    ],
    "dependencies": {
        "async": "^2.0.1",
        "gm": "^1.23.0",
        "joi": "^9.0.4",
        "mkdirp": "^0.5.1",
        "string": "^3.3.1",
        "yargs": "^6.3.0"
    },
    "description": "Slices a given image into tiles to be used for a interactive map display. (including command-line tool)",
    "devDependencies": {
        "standard": "^8.1.0",
        "tap": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "42ad21a06f996e56be61ea874fbfd5c4f727a2ed",
        "tarball": "https://registry.npmjs.org/mapslice/-/mapslice-1.3.0.tgz"
    },
    "gitHead": "85fb99de8736a67641c564bb80c7477ff19e03a2",
    "homepage": "https://github.com/martinheidegger/mapslice",
    "keywords": [
        "slice",
        "image",
        "manipulation"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "leichtgewicht"
        }
    ],
    "name": "mapslice",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/martinheidegger/mapslice.git"
    },
    "scripts": {
        "test": "standard && tap test/**/*.js"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
