# npmtest-i18next

#### test coverage for  [i18next (v7.2.3)](http://i18next.com)  [![npm package](https://img.shields.io/npm/v/npmtest-i18next.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-i18next) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-i18next.svg)](https://travis-ci.org/npmtest/node-npmtest-i18next)

#### i18next internationalization framework

[![NPM](https://nodei.co/npm/i18next.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18next)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-i18next/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18next/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-i18next/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-i18next/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-i18next/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-i18next/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-i18next/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-i18next/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-i18next/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-i18next/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-i18next/build/test-report.html](https://npmtest.github.io/node-npmtest-i18next/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-i18next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-i18next/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-i18next/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18next/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18next/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-i18next/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-i18next/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jan Mühlemann",
        "url": "https://github.com/jamuhl"
    },
    "bugs": {
        "url": "https://github.com/i18next/i18next/issues"
    },
    "dependencies": {},
    "description": "i18next internationalization framework",
    "devDependencies": {
        "babel-cli": "6.22.2",
        "babel-core": "6.22.1",
        "babel-eslint": "7.1.1",
        "babel-plugin-external-helpers": "6.22.0",
        "babel-plugin-transform-es2015-classes": "6.22.0",
        "babel-plugin-transform-proto-to-assign": "6.22.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-stage-0": "6.22.0",
        "babelify": "7.3.0",
        "browserify": "14.0.0",
        "browserify-istanbul": "2.0.0",
        "chai": "3.5.0",
        "coveralls": "2.11.16",
        "eslint": "3.15.0",
        "eslint-config-airbnb": "14.1.0",
        "eslint-plugin-import": "2.2.0",
        "eslint-plugin-jsx-a11y": "4.0.0",
        "eslint-plugin-react": "6.9.0",
        "i18next-browser-languagedetector": "1.0.1",
        "i18next-localstorage-cache": "0.3.0",
        "i18next-sprintf-postprocessor": "0.2.2",
        "i18next-xhr-backend": "1.3.0",
        "istanbul": "github:gotwarlost/istanbul#source-map",
        "karma": "1.4.1",
        "karma-browserify": "5.1.1",
        "karma-chai": "0.1.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-cli": "1.0.1",
        "karma-coverage": "github:douglasduteil/karma-coverage#next",
        "karma-coveralls": "1.1.2",
        "karma-expect": "1.1.3",
        "karma-mocha": "1.3.0",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-rollup-preprocessor": "3.0.3",
        "karma-sinon": "1.0.5",
        "karma-spec-reporter": "0.0.26",
        "mkdirp": "0.5.1",
        "mocha": "3.2.0",
        "phantomjs-prebuilt": "2.1.14",
        "rimraf": "2.5.4",
        "rollup": "0.41.4",
        "rollup-plugin-babel": "2.7.1",
        "rollup-plugin-node-resolve": "2.0.0",
        "rollup-plugin-uglify": "1.0.1",
        "sinon": "1.17.7",
        "watchify": "3.9.0",
        "yargs": "6.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a6c220ac1c8240ff1078aa9bc997fd449e052dc7",
        "tarball": "https://registry.npmjs.org/i18next/-/i18next-7.2.3.tgz"
    },
    "gitHead": "ca1a16f541d6be9cdb77b0b2d393b0ec4e6e38e6",
    "homepage": "http://i18next.com",
    "jsnext:main": "dist/es/index.js",
    "keywords": [
        "i18next",
        "internationalization",
        "i18n",
        "translation",
        "localization",
        "l10n",
        "globalization",
        "gettext"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "adrai"
        },
        {
            "name": "jamuhl"
        }
    ],
    "module": "dist/es/index.js",
    "name": "i18next",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/i18next/i18next.git"
    },
    "scripts": {
        "build": "npm run clean && npm run build:cjs && npm run build:es && npm run build:umd && npm run copy",
        "build:amd": "rollup -c rollup.config.js --format amd && rollup -c rollup.config.js --format umd --uglify",
        "build:cjs": "babel src --out-dir dist/commonjs",
        "build:es": "BABEL_ENV=jsnext babel src --out-dir dist/es",
        "build:iife": "rollup -c rollup.config.js --format iife && rollup -c rollup.config.js --format iife --uglify",
        "build:umd": "rollup -c rollup.config.js --format umd && rollup -c rollup.config.js --format umd --uglify",
        "clean": "rimraf dist && mkdirp dist",
        "copy": "cp ./dist/umd/i18next.min.js ./i18next.min.js && cp ./dist/umd/i18next.js ./i18next.js",
        "postversion": "git push && git push --tags",
        "preversion": "npm run test && npm run build && git push",
        "tdd": "karma start karma.conf.js",
        "tdd:compat": "karma start karma.backward.conf.js",
        "test": "npm run test:new && npm run test:compat",
        "test:compat": "karma start karma.backward.conf.js --singleRun",
        "test:new": "karma start karma.conf.js --singleRun"
    },
    "version": "7.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
