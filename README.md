# npmtest-static-site-generator-webpack-plugin

#### basic test coverage for  [static-site-generator-webpack-plugin (v3.4.1)](https://github.com/markdalgleish/static-site-generator-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-static-site-generator-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-static-site-generator-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-static-site-generator-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-static-site-generator-webpack-plugin)

#### Minimal, unopinionated static site generator powered by webpack

[![NPM](https://nodei.co/npm/static-site-generator-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/static-site-generator-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-static-site-generator-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-static-site-generator-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-static-site-generator-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "static-site-generator-webpack-plugin",
    "version": "3.4.1",
    "description": "Minimal, unopinionated static site generator powered by webpack",
    "main": "index.js",
    "scripts": {
        "test": "istanbul cover _mocha test -- --timeout 20000",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/markdalgleish/static-site-generator-webpack-plugin"
    },
    "author": "Mark Dalgleish",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/markdalgleish/static-site-generator-webpack-plugin/issues"
    },
    "homepage": "https://github.com/markdalgleish/static-site-generator-webpack-plugin",
    "dependencies": {
        "bluebird": "^3.0.5",
        "cheerio": "^0.22.0",
        "eval": "^0.1.0",
        "url": "^0.11.0",
        "webpack-sources": "^0.2.0"
    },
    "devDependencies": {
        "async": "^2.0.1",
        "babel-core": "^6.2.1",
        "babel-loader": "^6.2.0",
        "babel-preset-es2015": "^6.1.18",
        "chai": "^3.4.1",
        "compression-webpack-plugin": "^0.3.1",
        "coveralls": "^2.11.4",
        "ejs": "^2.3.4",
        "glob": "^7.0.3",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2",
        "rimraf": "^2.4.4",
        "webpack": "^1.12.10",
        "webpack-stats-plugin": "^0.1.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
