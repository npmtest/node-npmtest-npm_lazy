# npmtest-npm_lazy

#### basic test coverage for  [npm_lazy (v1.14.0)](https://github.com/mixu/npm_lazy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm_lazy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm_lazy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm_lazy.svg)](https://travis-ci.org/npmtest/node-npmtest-npm_lazy)

#### Lazy local npm cache server

[![NPM](https://nodei.co/npm/npm_lazy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm_lazy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm_lazy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm_lazy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm_lazy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm_lazy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm_lazy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm_lazy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm_lazy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm_lazy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm_lazy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm_lazy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm_lazy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm_lazy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm_lazy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm_lazy/build/test-report.html](https://npmtest.github.io/node-npmtest-npm_lazy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm_lazy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm_lazy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm_lazy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm_lazy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm_lazy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm_lazy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm_lazy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm_lazy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "npm_lazy": "./bin/npm_lazy"
    },
    "bugs": {
        "url": "https://github.com/mixu/npm_lazy/issues"
    },
    "dependencies": {
        "bytes": "~2.4.0",
        "file-fixture": "0.0.2",
        "microee": "0.0.6",
        "minilog": "~3.1.0",
        "mixu_minimal": "0.0.1",
        "mkdirp": "~0.5.1",
        "request": "~2.79.0",
        "yargs": "~6.6.0"
    },
    "description": "Lazy local npm cache server",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "feda1a7ab3a6b1da87a80234f151a46d79dc24e2",
        "tarball": "https://registry.npmjs.org/npm_lazy/-/npm_lazy-1.14.0.tgz"
    },
    "gitHead": "0291f72d4d0f0818189751675f8f0fe8de0f05d0",
    "homepage": "https://github.com/mixu/npm_lazy#readme",
    "keywords": [
        "mirror",
        "npm",
        "registry"
    ],
    "license": "BSD-3-Clause",
    "main": "./server.js",
    "maintainers": [
        {
            "name": "cl0sey"
        },
        {
            "name": "mixu"
        }
    ],
    "name": "npm_lazy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mixu/npm_lazy.git"
    },
    "scripts": {
        "start": "node server.js"
    },
    "version": "1.14.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
