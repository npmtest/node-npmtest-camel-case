# npmtest-camel-case

#### basic test coverage for  [camel-case (v3.0.0)](https://github.com/blakeembrey/camel-case)  [![npm package](https://img.shields.io/npm/v/npmtest-camel-case.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-camel-case) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-camel-case.svg)](https://travis-ci.org/npmtest/node-npmtest-camel-case)

#### Camel case a string

[![NPM](https://nodei.co/npm/camel-case.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/camel-case)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-camel-case/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-camel-case/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-camel-case/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-camel-case/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-camel-case/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-camel-case/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-camel-case/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-camel-case/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-camel-case/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-camel-case/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-camel-case/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-camel-case/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-camel-case/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-camel-case/build/test-report.html](https://npmtest.github.io/node-npmtest-camel-case/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-camel-case/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-camel-case/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-camel-case/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-camel-case/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-camel-case/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "url": "http://blakeembrey.me"
    },
    "bugs": {
        "url": "https://github.com/blakeembrey/camel-case/issues"
    },
    "dependencies": {
        "no-case": "^2.2.0",
        "upper-case": "^1.1.1"
    },
    "description": "Camel case a string",
    "devDependencies": {
        "istanbul": "^0.4.3",
        "mocha": "^2.2.1",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "ca3c3688a4e9cf3a4cda777dc4dcbc713249cf73",
        "tarball": "https://registry.npmjs.org/camel-case/-/camel-case-3.0.0.tgz"
    },
    "files": [
        "camel-case.js",
        "camel-case.d.ts",
        "LICENSE"
    ],
    "gitHead": "719ebc39a5bf828f794db64bb1a78c8dd8fef133",
    "homepage": "https://github.com/blakeembrey/camel-case",
    "keywords": [
        "camel",
        "case",
        "camelcase",
        "camel-case",
        "dash",
        "hyphen",
        "dot",
        "underscore",
        "lodash",
        "separator",
        "string",
        "text",
        "convert"
    ],
    "license": "MIT",
    "main": "camel-case.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        }
    ],
    "name": "camel-case",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/blakeembrey/camel-case.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec --bail",
        "test-spec": "mocha -- -R spec --bail"
    },
    "typings": "camel-case.d.ts",
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
