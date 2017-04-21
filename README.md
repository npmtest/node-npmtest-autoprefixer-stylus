# npmtest-autoprefixer-stylus

#### basic test coverage for  [autoprefixer-stylus (v0.13.0)](https://github.com/jescalan/autoprefixer-stylus#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-autoprefixer-stylus.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-autoprefixer-stylus) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-autoprefixer-stylus.svg)](https://travis-ci.org/npmtest/node-npmtest-autoprefixer-stylus)

#### autoprefixer for stylus

[![NPM](https://nodei.co/npm/autoprefixer-stylus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autoprefixer-stylus)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-autoprefixer-stylus/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-autoprefixer-stylus/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/test-report.html](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-autoprefixer-stylus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Escalante"
    },
    "bugs": {
        "url": "https://github.com/jescalan/autoprefixer-stylus/issues"
    },
    "dependencies": {
        "autoprefixer": "6.6.1",
        "multi-stage-sourcemap": "0.2.1",
        "postcss": "5.2.8"
    },
    "description": "autoprefixer for stylus",
    "devDependencies": {
        "chai": "3.5.0",
        "coffee-script": "1.12.1",
        "coveralls": "2.11.15",
        "css-parse": "2.0.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "stylus": "0.54.5"
    },
    "directories": {},
    "dist": {
        "shasum": "cc2a864e121fad691421c82d9f3e4328137b7df4",
        "tarball": "https://registry.npmjs.org/autoprefixer-stylus/-/autoprefixer-stylus-0.13.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "942b2da8be4a9d6e7b822e635e21b299be7c7a2f",
    "homepage": "https://github.com/jescalan/autoprefixer-stylus#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jescalan"
        }
    ],
    "name": "autoprefixer-stylus",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jescalan/autoprefixer-stylus.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha --report html -- -R spec && open coverage/index.html",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "test": "mocha"
    },
    "version": "0.13.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
