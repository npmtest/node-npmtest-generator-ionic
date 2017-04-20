# npmtest-generator-ionic

#### basic test coverage for  [generator-ionic (v0.8.0)](https://github.com/diegonetto/generator-ionic)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-ionic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-ionic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-ionic.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-ionic)

#### A generator for the Ionic Framework

[![NPM](https://nodei.co/npm/generator-ionic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-ionic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-ionic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-ionic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-ionic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-ionic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-ionic/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-ionic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-ionic/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-ionic/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-ionic/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-ionic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-ionic/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-ionic/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-ionic/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-ionic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-ionic/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-ionic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-ionic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-ionic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-ionic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-ionic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-ionic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-ionic",
    "version": "0.8.0",
    "description": "A generator for the Ionic Framework",
    "keywords": [
        "yeoman-generator",
        "ionic",
        "framework",
        "ionicframework",
        "angularjs",
        "hybrid",
        "mobile",
        "app"
    ],
    "homepage": "https://github.com/diegonetto/generator-ionic",
    "bugs": "https://github.com/diegonetto/generator-ionic/issues",
    "author": {
        "name": "Diego Netto",
        "url": "https://github.com/diegonetto"
    },
    "main": "app/index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/diegonetto/generator-ionic.git"
    },
    "scripts": {
        "test": "mocha --timeout 5000"
    },
    "dependencies": {
        "chalk": "^0.5.1",
        "cordova": "^4.2.0",
        "lodash": "^3.1.0",
        "mout": "^0.11.0",
        "npm-name": "^1.0.3",
        "superb": "^1.1.2",
        "yeoman-generator": "^0.18.7",
        "yosay": "^1.0.2"
    },
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-conventional-changelog": "^1.1.0",
        "grunt-release": "^0.11.0",
        "load-grunt-tasks": "^3.1.0",
        "marked": "^0.3.3",
        "mocha": "^2.1.0",
        "mockery": "^1.4.0",
        "semver": "^4.2.0"
    },
    "peerDependencies": {
        "yo": ">=1.0.0"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "licenses": [
        {
            "type": "MIT"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
