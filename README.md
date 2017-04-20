# npmtest-raml2html

#### basic test coverage for  [raml2html (v6.1.1)](https://github.com/raml2html/raml2html)  [![npm package](https://img.shields.io/npm/v/npmtest-raml2html.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-raml2html) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-raml2html.svg)](https://travis-ci.org/npmtest/node-npmtest-raml2html)

#### RAML to HTML documentation generator

[![NPM](https://nodei.co/npm/raml2html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raml2html)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-raml2html/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-raml2html/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-raml2html/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-raml2html/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-raml2html/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-raml2html/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-raml2html/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-raml2html/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-raml2html/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-raml2html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-raml2html/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-raml2html/build/test-report.html](https://npmtest.github.io/node-npmtest-raml2html/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-raml2html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-raml2html/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raml2html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-raml2html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-raml2html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "raml2html",
    "description": "RAML to HTML documentation generator",
    "version": "6.1.1",
    "author": {
        "name": "Kevin Renskers"
    },
    "bugs": {
        "url": "https://github.com/raml2html/raml2html/issues"
    },
    "dependencies": {
        "marked": "0.3.x",
        "minimize": "2.1.x",
        "nunjucks": "2.5.x",
        "nunjucks-markdown": "2.0.x",
        "raml2html-default-theme": "2.x",
        "raml2obj": "5.x",
        "yargs": "7.1.x"
    },
    "devDependencies": {
        "eslint": "3.19.x",
        "eslint-plugin-prettier": "2.0.x",
        "prettier": "1.x"
    },
    "homepage": "https://github.com/raml2html/raml2html",
    "keywords": [
        "RAML"
    ],
    "license": "MIT",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/raml2html/raml2html.git"
    },
    "preferGlobal": true,
    "scripts": {
        "lint": "eslint . --fix"
    },
    "bin": {
        "raml2html": "./bin/raml2html"
    },
    "files": [
        "index.js",
        "bin/raml2html"
    ],
    "engines": {
        "node": ">=4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
