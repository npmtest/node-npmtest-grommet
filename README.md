# npmtest-grommet

#### basic test coverage for  [grommet (v1.3.4)](http://grommet.io)  [![npm package](https://img.shields.io/npm/v/npmtest-grommet.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grommet) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grommet.svg)](https://travis-ci.org/npmtest/node-npmtest-grommet)

#### The most advanced UX framework for enterprise applications.

[![NPM](https://nodei.co/npm/grommet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grommet)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grommet/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grommet/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grommet/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grommet/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grommet/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grommet/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grommet/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grommet/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grommet/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grommet/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grommet/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grommet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grommet/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grommet/build/test-report.html](https://npmtest.github.io/node-npmtest-grommet/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grommet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grommet/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grommet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grommet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grommet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grommet/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grommet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grommet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Alan Souza",
        "Bryan Jacquot",
        "Chris Carlozzi",
        "Eric Soderberg"
    ],
    "bugs": {
        "url": "https://github.com/grommet/grommet/issues"
    },
    "dependencies": {
        "classnames": "^2.2.3",
        "deep-assign": "^2.0.0",
        "hammerjs": "^2.0.1",
        "intl": "^1.0.0",
        "inuit-defaults": "~0.2.1",
        "inuit-functions": "~0.2.0",
        "inuit-mixins": "~0.2.3",
        "inuit-normalize": "~4.1.1",
        "inuit-reset": "~0.1.1",
        "inuit-responsive-settings": "~0.1.2",
        "inuit-responsive-tools": "~0.1.1",
        "inuit-shared": "~0.1.5",
        "lodash.zip": "^4.2.0",
        "markdown-to-jsx": "^5.0.0",
        "moment": "^2.13.0",
        "react": "^15.3.0",
        "react-addons-transition-group": "^15.3.0",
        "react-desc": "^1.0.0",
        "react-dom": "^15.3.0",
        "react-intl": "^2.1.2",
        "react-router": "2 - 4",
        "superagent": "^3.3.1"
    },
    "description": "The most advanced UX framework for enterprise applications.",
    "devDependencies": {
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.0.0",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-plugin-transform-object-rest-spread": "^6.3.13",
        "babel-plugin-transform-react-es6-displayname": "^1.0.0-beta1.4",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "del": "^2.2.0",
        "eslint": "^3.13.1",
        "grommet-toolbox": "^1.0.0",
        "gulp": "^3.9.1",
        "gulp-bump": "^2.1.0",
        "gulp-coveralls": "^0.1.4",
        "gulp-cssnano": "^2.1.1",
        "gulp-file": "^0.3.0",
        "gulp-git": "^2.1.0",
        "gulp-if": "^2.0.0",
        "gulp-prompt": "^0.2.0",
        "gulp-rename": "^1.2.2",
        "gulp-sass": "^3.0.0",
        "guppy-pre-commit": "^0.4.0",
        "mkdirp": "^0.5.1",
        "node-sass": "^4.1.1",
        "react-test-renderer": "^15.3.0",
        "run-sequence": "^1.1.5",
        "webpack": "^1.12.14",
        "webpack-stream": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e921666acdd2819887ad0ae41447fbc3fe5dfbec",
        "tarball": "https://registry.npmjs.org/grommet/-/grommet-1.3.4.tgz"
    },
    "engine-strict": true,
    "engines": {
        "node": ">= 4.4.0"
    },
    "homepage": "http://grommet.io",
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alansouzati"
        },
        {
            "name": "ericsoderberg"
        }
    ],
    "name": "grommet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/grommet/grommet.git"
    },
    "scripts": {},
    "version": "1.3.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
