# npmtest-useragent

#### basic test coverage for  [useragent (v2.1.13)](https://github.com/3rd-Eden/useragent#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-useragent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-useragent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-useragent.svg)](https://travis-ci.org/npmtest/node-npmtest-useragent)

#### Fastest, most accurate & effecient user agent string parser, uses Browserscope's research for parsing

[![NPM](https://nodei.co/npm/useragent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/useragent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-useragent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-useragent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-useragent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-useragent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-useragent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-useragent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-useragent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-useragent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-useragent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-useragent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-useragent/build/test-report.html](https://npmtest.github.io/node-npmtest-useragent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-useragent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-useragent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-useragent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-useragent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-useragent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-useragent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/3rd-Eden/useragent/issues"
    },
    "dependencies": {
        "lru-cache": "2.2.x",
        "tmp": "0.0.x"
    },
    "description": "Fastest, most accurate & effecient user agent string parser, uses Browserscope's research for parsing",
    "devDependencies": {
        "long-stack-traces": "0.1.x",
        "mocha": "*",
        "pre-commit": "0.0.x",
        "request": "2.9.x",
        "semver": "1.0.x",
        "should": "*",
        "yamlparser": "0.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "bba43e8aa24d5ceb83c2937473e102e21df74c10",
        "tarball": "https://registry.npmjs.org/useragent/-/useragent-2.1.13.tgz"
    },
    "gitHead": "8656b673d7a33506efa1709d3b5a6964c8755957",
    "homepage": "https://github.com/3rd-Eden/useragent#readme",
    "keywords": [
        "agent",
        "browser",
        "browserscope",
        "os",
        "parse",
        "parser",
        "ua",
        "ua-parse",
        "ua-parser",
        "user agent",
        "user",
        "user-agent",
        "useragent",
        "version"
    ],
    "license": {
        "type": "MIT",
        "url": "https://github.com/3rd-Eden/useragent/blob/master/LICENSE"
    },
    "main": "./index.js",
    "maintainers": [
        {
            "name": "v1"
        },
        {
            "name": "3rdeden"
        }
    ],
    "name": "useragent",
    "optionalDependencies": {},
    "pre-commit": [
        "test",
        "update"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/3rd-Eden/useragent.git"
    },
    "scripts": {
        "prepublish": "npm run update",
        "qa": "mocha --ui exports $(find test -name '*.qa.js')",
        "test": "mocha $(find test -name '*.test.js')",
        "update": "node ./bin/update.js"
    },
    "version": "2.1.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
