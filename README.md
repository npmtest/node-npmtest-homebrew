# npmtest-homebrew

#### basic test coverage for  homebrew (v0.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-homebrew.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-homebrew) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-homebrew.svg)](https://travis-ci.org/npmtest/node-npmtest-homebrew)

#### The missing package manager for OS X

[![NPM](https://nodei.co/npm/homebrew.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebrew)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-homebrew/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebrew/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-homebrew/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-homebrew/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-homebrew/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-homebrew/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-homebrew/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-homebrew/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-homebrew/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-homebrew/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-homebrew/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebrew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-homebrew/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-homebrew/build/test-report.html](https://npmtest.github.io/node-npmtest-homebrew/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-homebrew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-homebrew/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebrew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-homebrew/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-homebrew/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebrew",
    "version": "0.1.0",
    "description": "The missing package manager for OS X",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/afc163/homebrew"
    },
    "scripts": {
        "postinstall": "ruby -e \"$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)\""
    },
    "author": "afc163 <afc163@gmail.com>",
    "license": "ISC",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
