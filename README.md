# npmtest-j

#### basic test coverage for  j (v0.4.5)  [![npm package](https://img.shields.io/npm/v/npmtest-j.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-j) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-j.svg)](https://travis-ci.org/npmtest/node-npmtest-j)

#### CLI tool for working with spreadsheet files

[![NPM](https://nodei.co/npm/j.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/j)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-j/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-j/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-j/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-j/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-j/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-j/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-j/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-j/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-j/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-j/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-j/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-j/build/test-report.html](https://npmtest.github.io/node-npmtest-j/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-j/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-j/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-j/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-j/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-j/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "j",
    "version": "0.4.5",
    "author": "sheetjs",
    "description": "CLI tool for working with spreadsheet files",
    "keywords": [
        "excel",
        "xls",
        "xlsx",
        "xlsm",
        "xlsb",
        "ods",
        "dif",
        "csv",
        "sylk",
        "prn",
        "ods",
        "dbf",
        "office",
        "spreadsheet"
    ],
    "bin": {
        "j": "./bin/j.njs"
    },
    "files": [
        "LICENSE",
        "README.md",
        "bin",
        "j.js"
    ],
    "main": "./j",
    "dependencies": {
        "exit-on-epipe": "",
        "xlsx": "~0.9.1",
        "xlsjs": "~0.7.6",
        "harb": "~0.1.1",
        "concat-stream": "",
        "commander": ""
    },
    "devDependencies": {
        "mocha": ""
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/SheetJS/j.git"
    },
    "scripts": {
        "test": "make mocha"
    },
    "config": {
        "blanket": {
            "pattern": "[./j.js,./node_modules/xlsx/xlsx.js]"
        }
    },
    "bugs": {
        "url": "https://github.com/SheetJS/j/issues"
    },
    "license": "Apache-2.0",
    "engines": {
        "node": ">=0.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
