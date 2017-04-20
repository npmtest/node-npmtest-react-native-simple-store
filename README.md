# npmtest-react-native-simple-store

#### basic test coverage for  [react-native-simple-store (v1.1.0)](https://github.com/jasonmerino/react-native-simple-store#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-simple-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-simple-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-simple-store.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-simple-store)

#### A minimalistic wrapper around React Native's AsyncStorage.

[![NPM](https://nodei.co/npm/react-native-simple-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-simple-store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-simple-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-simple-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-simple-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-simple-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-simple-store/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-simple-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-simple-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-simple-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-simple-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-simple-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Merino"
    },
    "bugs": {
        "url": "https://github.com/jasonmerino/react-native-simple-store/issues"
    },
    "dependencies": {
        "lodash.merge": "^4.6.0"
    },
    "description": "A minimalistic wrapper around React Native's AsyncStorage.",
    "devDependencies": {
        "babel-cli": "^6.7.7",
        "babel-jest": "^9.0.3",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-stage-0": "^6.5.0",
        "jest-cli": "^13.2.3",
        "jsdox": "^0.4.10",
        "react": "^0.14.7",
        "react-native": "^0.22.0"
    },
    "directories": {},
    "dist": {
        "shasum": "69e91d6b91d362cd4ea12b0486df3eaf2f628b04",
        "tarball": "https://registry.npmjs.org/react-native-simple-store/-/react-native-simple-store-1.1.0.tgz"
    },
    "gitHead": "2bf2d3797370c2ce92e9958165969d2db9ef4fa5",
    "homepage": "https://github.com/jasonmerino/react-native-simple-store#readme",
    "jest": {
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "unmockedModulePathPatterns": [
            "<rootdir>/node_modules/react-native"
        ],
        "testFileExtensions": [
            "js"
        ],
        "collectCoverage": true
    },
    "keywords": [
        "React Native",
        "iOS",
        "Android",
        "AsyncStorage",
        "data store",
        "key value store"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "jasonmerino"
        }
    ],
    "name": "react-native-simple-store",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jasonmerino/react-native-simple-store.git"
    },
    "scripts": {
        "dist": "babel src -d dist",
        "gen-docs": "jsdox src/index.js --output docs",
        "preversion": "npm run dist -s ; npm run gen-docs -s",
        "test": "jest"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
