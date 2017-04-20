# npmtest-swagger-tools

#### basic test coverage for  [swagger-tools (v0.10.1)](https://github.com/apigee-127/swagger-tools)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger-tools.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger-tools)

#### Various tools for using and integrating with Swagger.

[![NPM](https://nodei.co/npm/swagger-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-tools)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swagger-tools/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-tools/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-tools/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swagger-tools/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-tools/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swagger-tools/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swagger-tools/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swagger-tools/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swagger-tools/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swagger-tools/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swagger-tools/build/test-report.html](https://npmtest.github.io/node-npmtest-swagger-tools/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swagger-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swagger-tools/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swagger-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-tools/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swagger-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swagger-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "swagger-tools",
    "version": "0.10.1",
    "description": "Various tools for using and integrating with Swagger.",
    "main": "index.js",
    "scripts": {
        "test": "./node_modules/gulp/bin/gulp.js"
    },
    "author": {
        "name": "Jeremy Whitlock",
        "url": "https://github.com/whitlockjc"
    },
    "bugs": {
        "url": "https://github.com/apigee-127/swagger-tools/issues"
    },
    "homepage": "https://github.com/apigee-127/swagger-tools",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/apigee-127/swagger-tools.git"
    },
    "keywords": [
        "api",
        "connect",
        "middleware",
        "swagger"
    ],
    "bin": {
        "swagger-tools": "./bin/swagger-tools"
    },
    "files": [
        "bin",
        "index.js",
        "LICENSE",
        "lib",
        "middleware",
        "schemas"
    ],
    "devDependencies": {
        "browserify": "^10.2.4",
        "connect": "^3.4.0",
        "del": "^1.2.0",
        "exposify": "^0.4.3",
        "gulp": "^3.9.0",
        "gulp-if": "^1.2.5",
        "gulp-istanbul": "^0.10.0",
        "gulp-jshint": "^1.11.2",
        "gulp-load-plugins": "^0.10.0",
        "gulp-mocha": "^2.1.3",
        "gulp-uglify": "^1.2.0",
        "jshint-stylish": "^2.0.1",
        "karma": "^0.13.3",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^1.0.4",
        "karma-phantomjs-launcher": "^0.2.0",
        "mocha": "^2.2.5",
        "phantomjs": "^1.9.17",
        "run-sequence": "^1.1.1",
        "supertest": "^1.0.1",
        "vinyl-browserify": "0.0.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "dependencies": {
        "async": "^1.3.0",
        "body-parser": "1.12.4",
        "commander": "^2.8.1",
        "debug": "^2.2.0",
        "js-yaml": "^3.3.1",
        "json-refs": "^2.1.5",
        "lodash-compat": "^3.10.0",
        "multer": "^1.1.0",
        "parseurl": "^1.3.0",
        "path-to-regexp": "^1.2.0",
        "qs": "^4.0.0",
        "serve-static": "^1.10.0",
        "spark-md5": "^1.0.0",
        "string": "^3.3.0",
        "superagent": "^1.2.0",
        "swagger-converter": "^0.1.7",
        "traverse": "^0.6.6",
        "z-schema": "^3.15.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
