# npmtest-editorconfig

#### basic test coverage for  editorconfig (v0.13.2)  [![npm package](https://img.shields.io/npm/v/npmtest-editorconfig.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-editorconfig) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-editorconfig.svg)](https://travis-ci.org/npmtest/node-npmtest-editorconfig)

#### EditorConfig File Locator and Interpreter for Node.js

[![NPM](https://nodei.co/npm/editorconfig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/editorconfig)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-editorconfig/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-editorconfig/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-editorconfig/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-editorconfig/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-editorconfig/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-editorconfig/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-editorconfig/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-editorconfig/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-editorconfig/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-editorconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-editorconfig/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-editorconfig/build/test-report.html](https://npmtest.github.io/node-npmtest-editorconfig/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-editorconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-editorconfig/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-editorconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-editorconfig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-editorconfig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "editorconfig",
    "version": "0.13.2",
    "description": "EditorConfig File Locator and Interpreter for Node.js",
    "keywords": [
        "editorconfig",
        "core"
    ],
    "main": "editorconfig.js",
    "bin": {
        "editorconfig": "bin/editorconfig"
    },
    "contributors": [
        "Hong Xu (topbug.net)",
        "Jed Mao (https://github.com/jedmao/)",
        "Trey Hunner (http://treyhunner.com)"
    ],
    "directories": {
        "bin": "./bin",
        "lib": "./lib"
    },
    "scripts": {
        "pretest": "cmake .",
        "test": "npm run lint && ctest .",
        "test-verbose": "npm run lint && ctest -VV --output-on-failure .",
        "lint": "eclint check --indent_size ignore editorconfig.js README.md \"bin/**\" \"lib/**\""
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/editorconfig/editorconfig-core-js.git"
    },
    "bugs": "https://github.com/editorconfig/editorconfig-core-js/issues",
    "author": "EditorConfig Team",
    "license": {
        "type": "MIT",
        "url": "http://editorconfig.mit-license.org/2012"
    },
    "dependencies": {
        "bluebird": "^3.0.5",
        "commander": "^2.9.0",
        "lru-cache": "^3.2.0",
        "sigmund": "^1.0.1"
    },
    "devDependencies": {
        "eclint": "^1.1.5",
        "mocha": "^2.3.4",
        "should": "^7.1.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
