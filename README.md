# test coverage for  [selenium-standalone (v6.2.0)](https://github.com/vvo/selenium-standalone)  [![npm package](https://img.shields.io/npm/v/npmtest-selenium-standalone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-selenium-standalone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-selenium-standalone.svg)](https://travis-ci.org/npmtest/node-npmtest-selenium-standalone)
#### installs a `selenium-standalone` command line to install and start a standalone selenium server

[![NPM](https://nodei.co/npm/selenium-standalone.png?downloads=true)](https://www.npmjs.com/package/selenium-standalone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-selenium-standalone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-selenium-standalone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-selenium-standalone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-selenium-standalone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-selenium-standalone/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-selenium-standalone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-selenium-standalone/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-selenium-standalone/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-selenium-standalone/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-selenium-standalone/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-selenium-standalone%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-selenium-standalone/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-selenium-standalone/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-selenium-standalone%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-selenium-standalone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-selenium-standalone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-selenium-standalone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vincent Voyer",
        "email": "vincent@zeroload.net"
    },
    "bin": {
        "selenium-standalone": "./bin/selenium-standalone",
        "start-selenium": "./bin/start-selenium"
    },
    "bugs": {
        "url": "https://github.com/vvo/selenium-standalone/issues"
    },
    "contributors": [
        {
            "name": "Vincent Voyer",
            "email": "vincent@zeroload.net"
        },
        {
            "name": "Josh Chisholm",
            "email": "joshuachisholm@gmail.com"
        }
    ],
    "dependencies": {
        "async": "^2.1.4",
        "commander": "^2.9.0",
        "debug": "^2.6.3",
        "lodash": "^4.17.4",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "progress": "1.1.8",
        "request": "2.79.0",
        "tar-stream": "1.5.2",
        "urijs": "^1.18.4",
        "which": "^1.2.12",
        "yauzl": "^2.5.0"
    },
    "description": "installs a 'selenium-standalone' command line to install and start a standalone selenium server",
    "devDependencies": {
        "chai": "3.5.0",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6977642769de23f3b5ddce880a93fe1cf220fe01",
        "tarball": "https://registry.npmjs.org/selenium-standalone/-/selenium-standalone-6.2.0.tgz"
    },
    "gitHead": "12eb9ef8ef2aea2e9140d13b8b21ba6e102fb594",
    "homepage": "https://github.com/vvo/selenium-standalone",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "azakus",
            "email": "dfreedm2@gmail.com"
        },
        {
            "name": "c2c",
            "email": "contact@juliencrouzet.fr"
        },
        {
            "name": "devpaul",
            "email": "a@devpaul.com"
        },
        {
            "name": "nolanlawson",
            "email": "nolan@nolanlawson.com"
        },
        {
            "name": "stephenash",
            "email": "stephenash@gmail.com"
        },
        {
            "name": "vvo",
            "email": "vincent.voyer@gmail.com"
        }
    ],
    "name": "selenium-standalone",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/vvo/selenium-standalone.git"
    },
    "scripts": {
        "test": "./bin/selenium-standalone install && mocha"
    },
    "version": "6.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
