# npmtest-node-localstorage [![npm package](https://img.shields.io/npm/v/npmtest-node-localstorage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-localstorage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-localstorage.svg)](https://travis-ci.org/npmtest/node-npmtest-node-localstorage)

test coverage for  [node-localstorage (v1.3.0)](https://github.com/lmaccherone/node-localstorage)
#### A drop-in substitute for the browser native localStorage API that runs on node.js.

[![NPM](https://nodei.co/npm/node-localstorage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-localstorage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-localstorage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-localstorage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-localstorage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-localstorage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-localstorage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-localstorage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-localstorage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-localstorage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-localstorage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-localstorage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-localstorage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-localstorage/build/test-report.html](https://npmtest.github.io/node-npmtest-node-localstorage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-localstorage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-localstorage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-localstorage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-localstorage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-localstorage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-localstorage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-localstorage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-localstorage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Larry Maccherone",
        "url": "http://maccherone.com"
    },
    "bugs": {
        "url": "https://github.com/lmaccherone/node-localstorage/issues"
    },
    "dependencies": {
        "write-file-atomic": "^1.1.4"
    },
    "description": "A drop-in substitute for the browser native localStorage API that runs on node.js.",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "lodash": "^3.10.1",
        "nodeunit": "~0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2e436aae8dcc9ace97b43c65c16c0d577be0a55c",
        "tarball": "https://registry.npmjs.org/node-localstorage/-/node-localstorage-1.3.0.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "ec50d720c0917a853824e1a06e575bdbbb687a24",
    "homepage": "https://github.com/lmaccherone/node-localstorage",
    "keywords": [
        "localStorage",
        "Web Storage",
        "node.js"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "./LocalStorage",
    "maintainers": [
        {
            "name": "lmaccherone"
        }
    ],
    "name": "node-localstorage",
    "optionalDependencies": {},
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/lmaccherone/node-localstorage.git"
    },
    "scripts": {
        "docompile": "cake compile",
        "prepublish": "cake compile",
        "test": "cake test"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
