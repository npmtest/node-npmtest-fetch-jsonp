# npmtest-fetch-jsonp

#### basic test coverage for  [fetch-jsonp (v1.0.6)](https://github.com/camsong/fetch-jsonp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fetch-jsonp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fetch-jsonp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fetch-jsonp.svg)](https://travis-ci.org/npmtest/node-npmtest-fetch-jsonp)

#### Fetch JSONP like a boss using Fetch API

[![NPM](https://nodei.co/npm/fetch-jsonp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fetch-jsonp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fetch-jsonp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fetch-jsonp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fetch-jsonp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fetch-jsonp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fetch-jsonp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fetch-jsonp/build/test-report.html](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fetch-jsonp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fetch-jsonp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fetch-jsonp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fetch-jsonp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fetch-jsonp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cam Song"
    },
    "bugs": {
        "url": "https://github.com/camsong/fetch-jsonp/issues"
    },
    "dependencies": {},
    "description": "Fetch JSONP like a boss using Fetch API",
    "devDependencies": {
        "babel": "^5.8.21",
        "babel-core": "^5.8.21",
        "babel-eslint": "^4.0.5",
        "chai": "^3.2.0",
        "eslint": "^1.1.0",
        "eslint-config-airbnb": "^0.0.7",
        "eslint-plugin-react": "^3.2.1",
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "8d2ae174ed14108292f025f43fa07d2078de6736",
        "tarball": "https://registry.npmjs.org/fetch-jsonp/-/fetch-jsonp-1.0.6.tgz"
    },
    "gitHead": "3b1be53776fa36a548fbf2aa16063c27ca318661",
    "homepage": "https://github.com/camsong/fetch-jsonp#readme",
    "keywords": [
        "fetch",
        "jsonp",
        "github fetch",
        "ajax"
    ],
    "license": "MIT",
    "main": "build/fetch-jsonp.js",
    "maintainers": [
        {
            "name": "camsong"
        }
    ],
    "name": "fetch-jsonp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/camsong/fetch-jsonp.git"
    },
    "scripts": {
        "build": "babel src/ --modules umd --out-dir build",
        "clean": "rm -rf build",
        "lint": "eslint src/ test/",
        "test": "mocha --compilers js:babel/register --recursive --ui bdd --reporter spec"
    },
    "version": "1.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
