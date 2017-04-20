# npmtest-gulp-angular-protractor

#### basic test coverage for  gulp-angular-protractor (v0.4.2)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-angular-protractor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-angular-protractor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-angular-protractor.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-angular-protractor)

#### Based on the gulp-protractor plugin with an option to start / stop automatically the webdriver server

[![NPM](https://nodei.co/npm/gulp-angular-protractor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-angular-protractor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-angular-protractor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-angular-protractor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-angular-protractor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-angular-protractor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-angular-protractor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-angular-protractor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-angular-protractor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-angular-protractor",
    "version": "0.4.2",
    "description": "Based on the gulp-protractor plugin with an option to start / stop automatically the webdriver server",
    "license": "MIT",
    "repository": "rochejul/gulp-angular-protractor",
    "author": {
        "name": "Julien Roche",
        "url": "https://github.com/rochejul"
    },
    "engineStrict": true,
    "engines": {
        "node": ">=6.9.x",
        "npm": ">=3.10.8"
    },
    "scripts": {
        "bump-release": "npm test && npm run npmversion -- --unpreid --git-push",
        "bump-major": "npm test && npm run npmversion -- --increment major --git-push",
        "bump-minor": "npm test && npm run npmversion -- --increment minor --git-push",
        "bump-patch": "npm test && npm run npmversion -- --increment patch --git-push",
        "bump-major-beta": "npm run npmversion -- --increment major --preid beta --nogit-tag --git-push",
        "bump-minor-beta": "npm run npmversion -- --increment minor --preid beta --nogit-tag --git-push",
        "bump-patch-beta": "npm run npmversion -- --increment patch --preid beta --nogit-tag --git-push",
        "npmversion": "node ./node_modules/npmversion/bin/npmversion",
        "snapshot": "npm shrinkwrap --only=prod",
        "test": "mocha --recursive --colors test/"
    },
    "files": [
        "index.js",
        "gulp-angular-protractor",
        "npm-shrinkwrap.json"
    ],
    "keywords": [
        "gulpplugin"
    ],
    "dependencies": {
        "event-stream": "3.1.5",
        "gulp-util": "3.0.1",
        "lodash": "2.4.1",
        "protractor": "4.0.11",
        "webdriver-manager": "10.2.8"
    },
    "devDependencies": {
        "chai": "1.10.0",
        "eslint": "2.4.0",
        "eslint-plugin-node": "2.0.0",
        "mocha": "*",
        "nock": "0.53.0",
        "npmversion": "1.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
