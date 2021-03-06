# npmtest-webpack

#### basic test coverage for  [webpack (v2.4.1)](https://github.com/webpack/webpack)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack)

#### Packs CommonJs/AMD modules for the browser. Allows to split your codebase into multiple bundles, which can be loaded on demand. Support loaders to preprocess files, i.e. json, jsx, es7, css, less, ... and your custom stuff.

[![NPM](https://nodei.co/npm/webpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-webpack/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-webpack/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bin": {
        "webpack": "./bin/webpack.js"
    },
    "bugs": {
        "url": "https://github.com/webpack/webpack/issues"
    },
    "dependencies": {
        "acorn": "^5.0.0",
        "acorn-dynamic-import": "^2.0.0",
        "ajv": "^4.7.0",
        "ajv-keywords": "^1.1.1",
        "async": "^2.1.2",
        "enhanced-resolve": "^3.0.0",
        "interpret": "^1.0.0",
        "json-loader": "^0.5.4",
        "json5": "^0.5.1",
        "loader-runner": "^2.3.0",
        "loader-utils": "^0.2.16",
        "memory-fs": "~0.4.1",
        "mkdirp": "~0.5.0",
        "node-libs-browser": "^2.0.0",
        "source-map": "^0.5.3",
        "supports-color": "^3.1.0",
        "tapable": "~0.2.5",
        "uglify-js": "^2.8.5",
        "watchpack": "^1.3.1",
        "webpack-sources": "^0.2.3",
        "yargs": "^6.0.0"
    },
    "description": "Packs CommonJs/AMD modules for the browser. Allows to split your codebase into multiple bundles, which can be loaded on demand. Support loaders to preprocess files, i.e. json, jsx, es7, css, less, ... and your custom stuff.",
    "devDependencies": {
        "beautify-lint": "^1.0.3",
        "benchmark": "^2.1.1",
        "bundle-loader": "~0.5.0",
        "codacy-coverage": "^2.0.1",
        "codecov.io": "^0.1.2",
        "coffee-loader": "~0.7.1",
        "coffee-script": "^1.10.0",
        "coveralls": "^2.11.2",
        "css-loader": "~0.25.0",
        "es6-promise-polyfill": "^1.1.1",
        "eslint": "3.12.2",
        "eslint-plugin-node": "^3.0.5",
        "express": "~4.13.1",
        "extract-text-webpack-plugin": "^2.0.0-beta",
        "file-loader": "~0.9.0",
        "i18n-webpack-plugin": "^0.3.0",
        "istanbul": "^0.4.5",
        "jade": "^1.11.0",
        "jade-loader": "~0.8.0",
        "js-beautify": "^1.5.10",
        "less": "^2.5.1",
        "less-loader": "^2.0.0",
        "lodash": "^4.17.4",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "^1.0.0",
        "nsp": "^2.6.1",
        "raw-loader": "~0.5.0",
        "react": "^15.2.1",
        "react-dom": "^15.2.1",
        "script-loader": "~0.7.0",
        "should": "^11.1.1",
        "simple-git": "^1.65.0",
        "sinon": "^1.17.7",
        "style-loader": "~0.13.0",
        "url-loader": "~0.5.0",
        "val-loader": "~0.5.0",
        "vm-browserify": "~0.0.0",
        "webpack-dev-middleware": "^1.9.0",
        "worker-loader": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "15a91dbe34966d8a4b99c7d656efd92a2e5a6f6a",
        "tarball": "https://registry.npmjs.org/webpack/-/webpack-2.4.1.tgz"
    },
    "engines": {
        "node": ">=4.3.0 <5.0.0 || >=5.10"
    },
    "files": [
        "lib/",
        "bin/",
        "buildin/",
        "hot/",
        "web_modules/",
        "schemas/"
    ],
    "gitHead": "bd753567da1248624beaaea14af31d6dbe303411",
    "homepage": "https://github.com/webpack/webpack",
    "license": "MIT",
    "main": "lib/webpack.js",
    "maintainers": [
        {
            "name": "jhnns"
        },
        {
            "name": "sokra"
        },
        {
            "name": "thelarkinn"
        }
    ],
    "name": "webpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/webpack/webpack.git"
    },
    "scripts": {
        "appveyor:benchmark": "npm run benchmark",
        "appveyor:test": "node --max_old_space_size=4096 node_modules\\mocha\\bin\\mocha --harmony test/*.test.js",
        "beautify-lint": "beautify-lint 'lib/**/*.js' 'hot/**/*.js' 'bin/**/*.js' 'benchmark/*.js' 'test/*.js'",
        "benchmark": "mocha test/*.benchmark.js --harmony -R spec",
        "build:examples": "cd examples && node buildAll.js",
        "cover": "node --harmony ./node_modules/istanbul/lib/cli.js cover -x '**/*.runtime.js' node_modules/mocha/bin/_mocha -- test/*.test.js",
        "cover:min": "node --harmony ./node_modules/.bin/istanbul cover -x '**/*.runtime.js' --report lcovonly node_modules/mocha/bin/_mocha -- test/*.test.js",
        "lint": "eslint lib bin hot buildin test/**/webpack.config.js test/binCases/**/test.js examples/**/webpack.config.js",
        "lint-files": "npm run lint && npm run beautify-lint",
        "nsp": "nsp check --output summary",
        "pretest": "npm run lint-files",
        "publish-patch": "npm run lint && npm run beautify-lint && mocha && npm version patch && git push && git push --tags && npm publish",
        "test": "mocha test/*.test.js --harmony --check-leaks",
        "travis:benchmark": "npm run benchmark",
        "travis:lint": "npm run lint-files && npm run nsp",
        "travis:test": "npm run cover:min"
    },
    "version": "2.4.1",
    "web": "lib/webpack.web.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
