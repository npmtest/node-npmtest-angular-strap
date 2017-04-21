# npmtest-angular-strap

#### basic test coverage for  [angular-strap (v2.3.12)](http://mgcrea.github.io/angular-strap)  [![npm package](https://img.shields.io/npm/v/npmtest-angular-strap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular-strap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular-strap.svg)](https://travis-ci.org/npmtest/node-npmtest-angular-strap)

#### AngularStrap - AngularJS directives for Bootstrap

[![NPM](https://nodei.co/npm/angular-strap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular-strap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular-strap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-strap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular-strap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular-strap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular-strap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular-strap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular-strap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular-strap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular-strap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-strap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular-strap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular-strap/build/test-report.html](https://npmtest.github.io/node-npmtest-angular-strap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular-strap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular-strap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular-strap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular-strap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-strap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-strap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular-strap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular-strap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "angular-strap",
    "description": "AngularStrap - AngularJS directives for Bootstrap",
    "version": "2.3.12",
    "keywords": [
        "angular",
        "bootstrap"
    ],
    "main": "index.js",
    "homepage": "http://mgcrea.github.io/angular-strap",
    "bugs": "https://github.com/mgcrea/angular-strap/issues",
    "author": {
        "name": "Olivier Louvignes",
        "url": "https://github.com/mgcrea"
    },
    "contributors": [
        {
            "name": "Vitor Fernandes",
            "url": "https://github.com/vmlf01"
        },
        {
            "name": "Dale Alexander Webb",
            "url": "https://github.com/DaleWebb"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/mgcrea/angular-strap.git"
    },
    "license": "MIT",
    "dependencies": {},
    "devDependencies": {
        "codeclimate-test-reporter": "^0.3.2",
        "del": "^2.2.0",
        "eslint": "^2.12.0",
        "eslint-config-mgcrea": "^8.0.0",
        "eslint-plugin-import": "^1.8.1",
        "factory-angular-channels": "^0.10.0",
        "gulp-ng-annotate": "^2.0.0",
        "gulp-pre": "^4.0.0-alpha.4",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.5.3",
        "gulp-util": "^3.0.7",
        "jasmine-core": "^2.4.1",
        "karma": "^0.13.22",
        "karma-chrome-launcher": "^1.0.1",
        "karma-coverage": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-sauce-launcher": "^1.0.0",
        "ng-factory": "^1.1.0",
        "phantomjs-prebuilt": "^2.1.7",
        "through2": "^2.0.1",
        "undertaker-lib-tasks": "^0.5.3"
    },
    "scripts": {
        "start": "gulp serve",
        "compile": "gulp build",
        "test": "gulp karma:unit",
        "test:watch": "npm run test -- -w",
        "lint": "eslint src/*/*.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
