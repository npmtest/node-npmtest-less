# npmtest-less

#### test coverage for  [less (v2.7.2)](http://lesscss.org)  [![npm package](https://img.shields.io/npm/v/npmtest-less.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-less) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-less.svg)](https://travis-ci.org/npmtest/node-npmtest-less)

#### Leaner CSS

[![NPM](https://nodei.co/npm/less.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/less)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-less/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-less/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-less/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-less/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-less/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-less/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-less/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-less/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-less/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-less/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-less/build/test-report.html](https://npmtest.github.io/node-npmtest-less/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-less/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-less/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-less/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-less/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-less/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-less/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexis Sellier"
    },
    "bin": {
        "lessc": "./bin/lessc"
    },
    "browser": "./dist/less.js",
    "bugs": {
        "url": "https://github.com/less/less.js/issues"
    },
    "contributors": [
        {
            "name": "The Core Less Team"
        }
    ],
    "dependencies": {
        "errno": "^0.1.1",
        "graceful-fs": "^4.1.2",
        "image-size": "~0.5.0",
        "mime": "^1.2.11",
        "mkdirp": "^0.5.0",
        "promise": "^7.1.1",
        "request": "^2.72.0",
        "source-map": "^0.5.3"
    },
    "description": "Leaner CSS",
    "devDependencies": {
        "diff": "^2.2.2",
        "grunt": "~0.4.5",
        "grunt-browserify": "^5.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-connect": "^1.0.2",
        "grunt-contrib-jasmine": "^1.0.3",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-jscs": "^2.8.0",
        "grunt-saucelabs": "^8.6.2",
        "grunt-shell": "^1.3.0",
        "jit-grunt": "^0.10.0",
        "phantomjs-prebuilt": "^2.1.7",
        "time-grunt": "^1.3.0"
    },
    "directories": {
        "test": "./test"
    },
    "dist": {
        "shasum": "368d6cc73e1fb03981183280918743c5dcf9b3df",
        "tarball": "https://registry.npmjs.org/less/-/less-2.7.2.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "ceb54053e7964342e6d9be44e24dad701d818098",
    "homepage": "http://lesscss.org",
    "jam": {
        "main": "./dist/less.js"
    },
    "keywords": [
        "compile less",
        "css nesting",
        "css variable",
        "css",
        "gradients css",
        "gradients css3",
        "less compiler",
        "less css",
        "less mixins",
        "less",
        "less.js",
        "lesscss",
        "mixins",
        "nested css",
        "parser",
        "preprocessor",
        "bootstrap css",
        "bootstrap less",
        "style",
        "styles",
        "stylesheet",
        "variables in css",
        "css less"
    ],
    "license": "Apache-2.0",
    "main": "index",
    "maintainers": [
        {
            "name": "agatronic"
        },
        {
            "name": "cloudhead"
        },
        {
            "name": "matthew-dean"
        },
        {
            "name": "meri"
        },
        {
            "name": "seven-phases-max"
        }
    ],
    "master": {
        "url": "https://github.com/less/less.js/blob/master/",
        "raw": "https://raw.githubusercontent.com/less/less.js/master/"
    },
    "name": "less",
    "optionalDependencies": {
        "errno": "^0.1.1",
        "graceful-fs": "^4.1.2",
        "image-size": "~0.5.0",
        "mime": "^1.2.11",
        "mkdirp": "^0.5.0",
        "promise": "^7.1.1",
        "request": "^2.72.0",
        "source-map": "^0.5.3"
    },
    "rawcurrent": "https://raw.github.com/less/less.js/v",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/less/less.js.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "sourcearchive": "https://github.com/less/less.js/archive/v",
    "version": "2.7.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
