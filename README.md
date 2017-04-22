# npmtest-ember-power-select

#### basic test coverage for  [ember-power-select (v1.7.2)](http://www.ember-power-select.com)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-power-select.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-power-select) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-power-select.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-power-select)

#### The extensible select component built for ember

[![NPM](https://nodei.co/npm/ember-power-select.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-power-select)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-power-select/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-power-select/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-power-select/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-power-select/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-power-select/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-power-select/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-power-select/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-power-select/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-power-select/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-power-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-power-select/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-power-select/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-power-select/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-power-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-power-select/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-power-select/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-power-select/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-power-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-power-select/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-power-select/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-power-select/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Miguel Camba"
    },
    "bugs": {
        "url": "https://github.com/cibernox/ember-power-select/issues"
    },
    "dependencies": {
        "ember-basic-dropdown": "^0.31.4",
        "ember-cli-babel": "^6.0.0-beta.9",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-concurrency": "^0.8.1",
        "ember-text-measurer": "^0.3.3",
        "ember-truth-helpers": "^1.3.0"
    },
    "description": "The extensible select component built for ember",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "ember-cli": "^2.13.0-beta.3",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-blueprint-test-helpers": "0.14.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-deploy": "0.5.0",
        "ember-cli-eslint": "^3.0.0",
        "ember-cli-htmlbars-inline-precompile": "^0.4.0-beta.2",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-mirage": "0.2.8",
        "ember-cli-qunit": "^4.0.0-beta.1",
        "ember-cli-release": "1.0.0-beta.2",
        "ember-cli-sass": "^6.1.1",
        "ember-cli-shims": "^1.1.0",
        "ember-cli-template-lint": "0.4.12",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-code-example-component": "^0.1.1",
        "ember-code-snippet": "1.8.1",
        "ember-data": "^2.12.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^2.0.0",
        "ember-fastboot-test-helpers": "0.1.1",
        "ember-fetch": "github:cibernox/ember-fetch#make-it-wait",
        "ember-href-to": "1.12.0",
        "ember-load-initializers": "^1.0.0",
        "ember-maybe-import-regenerator": "^0.1.6",
        "ember-native-dom-event-dispatcher": "^0.5.4",
        "ember-native-dom-helpers": "^0.3.9",
        "ember-pagefront": "0.10.10",
        "ember-resolver": "^4.0.0",
        "ember-source": "~2.13.0-beta.2",
        "eslint-plugin-ember-suave": "^1.0.0",
        "liquid-fire": "0.26.7",
        "loader.js": "^4.2.3",
        "memory-scroll": "0.9.0",
        "mocha": "2.5.3",
        "simple-git": "^1.10.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "d73da0f1dca8c5bd970dbf5ce29b81af7faff6a7",
        "tarball": "https://registry.npmjs.org/ember-power-select/-/ember-power-select-1.7.2.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "before": "ember-cli-sri"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "files": [
        "addon/",
        "app/",
        "blueprints/",
        "test-support/",
        "index.js",
        "vendor"
    ],
    "gitHead": "c22ce196f46baf928d42e7f61d765ff7e8ecb5e7",
    "homepage": "http://www.ember-power-select.com",
    "keywords": [
        "ember-addon",
        "select",
        "select2",
        "selectize",
        "dropdown"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "cibernox"
        }
    ],
    "name": "ember-power-select",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/cibernox/ember-power-select.git"
    },
    "scripts": {
        "build": "ember build",
        "nodetest": "mocha node-tests --recursive",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "1.7.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
