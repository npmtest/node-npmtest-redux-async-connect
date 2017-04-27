# npmtest-redux-async-connect

#### basic test coverage for  [redux-async-connect (v0.1.13)](https://github.com/Rezonans/redux-async-connect)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-async-connect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-async-connect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-async-connect.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-async-connect)

#### It allows you to request async data, store them in redux state and connect them to your react component.

[![NPM](https://nodei.co/npm/redux-async-connect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-async-connect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-async-connect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-async-connect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-async-connect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-async-connect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-async-connect/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-redux-async-connect/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-redux-async-connect/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-async-connect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-async-connect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-async-connect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-async-connect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-async-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-async-connect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-async-connect/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-async-connect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-async-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-async-connect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-async-connect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-async-connect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rodion Salnik",
        "url": "http://brocoders.com"
    },
    "bugs": {
        "url": "https://github.com/Rezonans/redux-async-connect/issues"
    },
    "dependencies": {},
    "description": "It allows you to request async data, store them in redux state and connect them to your react component.",
    "devDependencies": {
        "babel-cli": "^6.4.5",
        "babel-core": "^6.4.5",
        "babel-eslint": "^5.0.0-beta6",
        "babel-loader": "^6.2.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "eslint": "1.4.1",
        "eslint-config-airbnb": "^3.1.0",
        "eslint-config-rackt": "1.0.0",
        "eslint-plugin-react": "3.3.2",
        "expect": "^1.12.0",
        "express": "^4.13.3",
        "gzip-size": "^3.0.0",
        "history": "^1.13.1",
        "karma": "^0.13.3",
        "karma-browserstack-launcher": "^0.1.3",
        "karma-chrome-launcher": "^0.2.0",
        "karma-firefox-launcher": "^0.1.6",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^1.0.4",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.0.1",
        "pretty-bytes": "^2.0.1",
        "react": "^0.14.2",
        "react-dom": "^0.14.2",
        "react-router": "2.0.0-rc5",
        "rimraf": "^2.4.2",
        "webpack": "^1.12.6",
        "webpack-dev-middleware": "^1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0a981f2e1952e4ad7a56cb9d1d305d8668cc808b",
        "tarball": "https://registry.npmjs.org/redux-async-connect/-/redux-async-connect-0.1.13.tgz"
    },
    "gitHead": "7d273f0b926cf668f1cfd23c379c917aca35b40f",
    "homepage": "https://github.com/Rezonans/redux-async-connect",
    "keywords": [
        "redux",
        "react",
        "connect",
        "async",
        "props"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "sarssokol"
        }
    ],
    "name": "redux-async-connect",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "0.14.x",
        "react-router": "2.x.x",
        "react-redux": "4.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Rezonans/redux-async-connect.git"
    },
    "scripts": {
        "build": "babel ./modules -d lib --ignore '__tests__'",
        "lint": "eslint modules",
        "prepublish": "node ./npm-scripts/postinstall.js",
        "start": "babel-node example/server.js",
        "test": "npm run lint && karma start"
    },
    "version": "0.1.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
