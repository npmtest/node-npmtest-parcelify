# npmtest-parcelify

#### basic test coverage for  [parcelify (v2.2.0)](https://github.com/rotundasoftware/parcelify)  [![npm package](https://img.shields.io/npm/v/npmtest-parcelify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parcelify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parcelify.svg)](https://travis-ci.org/npmtest/node-npmtest-parcelify)

#### Create css bundles from npm packages using the browserify dependency graph.

[![NPM](https://nodei.co/npm/parcelify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parcelify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parcelify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parcelify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parcelify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parcelify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parcelify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parcelify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parcelify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parcelify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parcelify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parcelify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parcelify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parcelify/build/test-report.html](https://npmtest.github.io/node-npmtest-parcelify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parcelify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parcelify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parcelify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parcelify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parcelify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parcelify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parcelify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parcelify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rotunda Software"
    },
    "bin": {
        "parcelify": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/rotundasoftware/parcelify/issues"
    },
    "dependencies": {
        "async": "~0.2.10",
        "glob": "~3.2.9",
        "globwatcher": "~1.2.3",
        "inherits": "~2.0.1",
        "minimist": "0.0.8",
        "mkdirp": "~0.3.5",
        "npmlog": "0.0.6",
        "parcel-map": "^3.0.0",
        "resolve": "~0.6.1",
        "shasum": "~1.0.1",
        "stream-combiner": "^0.2.2",
        "through2": "~0.6.3",
        "toposort": "~0.2.10",
        "underscore": "~1.6.0"
    },
    "description": "Create css bundles from npm packages using the browserify dependency graph.",
    "devDependencies": {
        "browserify": "^9.0.8",
        "sass-css-stream": "^0.1.4",
        "tape": "~2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d77be17d13609e05e40f7409e1c4a162672c2391",
        "tarball": "https://registry.npmjs.org/parcelify/-/parcelify-2.2.0.tgz"
    },
    "gitHead": "5400f2a3faa960c712cad864e747ef0a42a0bd5a",
    "homepage": "https://github.com/rotundasoftware/parcelify",
    "keywords": [
        "parcel",
        "asset",
        "css",
        "commonjs",
        "browserify"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/rotundasoftware/parcelify/blob/master/LICENSE"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "rotundasoftware"
        },
        {
            "name": "go-oleg"
        },
        {
            "name": "davidbeck"
        },
        {
            "name": "substack"
        }
    ],
    "name": "parcelify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rotundasoftware/parcelify.git"
    },
    "scripts": {
        "test": "tape test/test.js"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
