# npmtest-jstransformer

#### basic test coverage for  jstransformer (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-jstransformer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jstransformer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jstransformer.svg)](https://travis-ci.org/npmtest/node-npmtest-jstransformer)

#### Normalize the API of any jstransformer

[![NPM](https://nodei.co/npm/jstransformer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jstransformer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jstransformer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jstransformer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jstransformer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jstransformer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jstransformer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jstransformer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jstransformer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jstransformer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jstransformer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jstransformer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jstransformer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jstransformer/build/test-report.html](https://npmtest.github.io/node-npmtest-jstransformer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jstransformer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jstransformer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jstransformer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jstransformer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jstransformer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jstransformer",
    "version": "1.0.0",
    "description": "Normalize the API of any jstransformer",
    "keywords": [
        "jstransformer"
    ],
    "dependencies": {
        "is-promise": "^2.0.0",
        "promise": "^7.0.1"
    },
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.4.0",
        "testit": "^2.0.2"
    },
    "scripts": {
        "test": "node test",
        "coverage": "istanbul cover test",
        "coveralls": "npm run coverage && cat ./coverage/lcov.info | coveralls"
    },
    "files": [
        "index.js"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/jstransformers/jstransformer.git"
    },
    "author": "ForbesLindesay",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
