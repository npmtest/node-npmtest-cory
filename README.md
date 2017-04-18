# npmtest-cory

#### test coverage for  [cory (v2.0.0)](https://github.com/leo/cory#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cory.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cory) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cory.svg)](https://travis-ci.org/npmtest/node-npmtest-cory)

#### Minimal generator for static sites

[![NPM](https://nodei.co/npm/cory.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cory)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cory/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cory/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cory/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cory/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cory/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cory/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cory/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cory/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cory/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cory/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cory/build/test-report.html](https://npmtest.github.io/node-npmtest-cory/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cory/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cory/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cory/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cory/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cory/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cory/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Leo Lamprecht",
        "url": "http://leo.im"
    },
    "ava": {
        "files": [
            "test/*.js"
        ]
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "bin": {
        "cory": "dist/bin/index",
        "cory-serve": "dist/bin/serve",
        "cory-build": "dist/bin/build",
        "cory-init": "dist/bin/init",
        "cory-clean": "dist/bin/clean"
    },
    "bugs": {
        "url": "https://github.com/leo/cory/issues"
    },
    "dependencies": {
        "args": "^1.3.1",
        "broccoli": "^0.16.9",
        "broccoli-sane-watcher": "^1.1.4",
        "browser-sync": "^2.13.0",
        "chokidar": "^1.6.0",
        "colors": "^1.1.2",
        "front-matter": "^2.1.0",
        "fs-extra": "^0.30.0",
        "handlebars": "^4.0.5",
        "markdown": "^0.5.0",
        "mime": "^1.3.4",
        "mkdirp": "^0.5.1",
        "ncp": "^2.0.0",
        "open": "0.0.5",
        "ora": "^0.2.3",
        "update-notifier": "^1.0.2",
        "walk": "^2.3.9"
    },
    "description": "Minimal generator for static sites",
    "devDependencies": {
        "ava": "^0.15.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-register": "^6.9.0",
        "eslint": "^3.0.1",
        "eslint-config-default": "^0.2.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-cached": "^1.1.0",
        "gulp-ext": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ef25d2d396dac9b934242eedf5b8d8fe349453ad",
        "tarball": "https://registry.npmjs.org/cory/-/cory-2.0.0.tgz"
    },
    "eslintConfig": {
        "extends": "default"
    },
    "files": [
        "template",
        "dist"
    ],
    "gitHead": "15a1a5f2c7505a38233879d4987a4bf204dfd1e5",
    "homepage": "https://github.com/leo/cory#readme",
    "keywords": [
        "static",
        "site",
        "generator",
        "jekyll",
        "content",
        "website"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "leo"
        }
    ],
    "name": "cory",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/leo/cory.git"
    },
    "scripts": {
        "prepublish": "gulp transpile",
        "pretest": "gulp transpile",
        "start": "gulp",
        "test": "ava && eslint bin/** lib/**"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
