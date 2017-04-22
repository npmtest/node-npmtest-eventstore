# npmtest-eventstore

#### basic test coverage for  [eventstore (v1.12.2)](https://github.com/adrai/node-eventstore)  [![npm package](https://img.shields.io/npm/v/npmtest-eventstore.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eventstore) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eventstore.svg)](https://travis-ci.org/npmtest/node-npmtest-eventstore)

#### Node-eventstore is a node.js module for multiple databases. It can be very useful as eventstore if you work with (d)ddd, cqrs, eventsourcing, commands and events, etc.

[![NPM](https://nodei.co/npm/eventstore.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventstore)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eventstore/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventstore/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eventstore/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eventstore/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eventstore/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eventstore/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eventstore/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eventstore/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eventstore/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventstore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eventstore/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eventstore/build/test-report.html](https://npmtest.github.io/node-npmtest-eventstore/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eventstore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eventstore/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eventstore/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventstore/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventstore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventstore/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eventstore/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eventstore/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "adrai"
    },
    "bugs": {
        "url": "https://github.com/adrai/node-eventstore/issues"
    },
    "contributors": [
        {
            "name": "Adriano Raiano"
        },
        {
            "name": "Jan Muehlemann"
        }
    ],
    "dependencies": {
        "async": "2.1.4",
        "debug": "2.6.0",
        "dotty": "0.0.2",
        "jsondate": "0.0.1",
        "lodash": "4.17.4",
        "parent-require": "1.0.0",
        "tolerance": "1.0.0",
        "uuid": "3.0.0"
    },
    "description": "Node-eventstore is a node.js module for multiple databases. It can be very useful as eventstore if you work with (d)ddd, cqrs, eventsourcing, commands and events, etc.",
    "devDependencies": {
        "aws-sdk": ">=2.4.9",
        "azure-storage": ">=0.10.0",
        "cradle": ">=0.7.1",
        "elasticsearch": ">=10.0.0",
        "eslint": ">=1.0.0",
        "expect.js": ">=0.1.2",
        "mocha": ">=1.0.1",
        "mongodb": ">=0.0.1",
        "redis": ">=0.10.1",
        "tingodb": ">=0.0.1",
        "uuid": "^3.0.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "c0ae885b75da074fc08260034a2b2668c7d20ff3",
        "tarball": "https://registry.npmjs.org/eventstore/-/eventstore-1.12.2.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "69f0e9a0e3f301d6c43579fb7bad891aeeb0bcf0",
    "homepage": "https://github.com/adrai/node-eventstore",
    "keywords": [
        "cqrs",
        "eventstore",
        "ddd",
        "(d)ddd",
        "eventsourcing",
        "mongodb",
        "redis",
        "tingodb",
        "azure",
        "azuretable",
        "inmemory",
        "elasticsearch"
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "jamuhl"
        },
        {
            "name": "adrai"
        }
    ],
    "name": "eventstore",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/adrai/node-eventstore.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.12.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
