# npmtest-rollup-plugin-babel

#### test coverage for  [rollup-plugin-babel (v2.7.1)](https://github.com/rollup/rollup-plugin-babel)  [![npm package](https://img.shields.io/npm/v/npmtest-rollup-plugin-babel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rollup-plugin-babel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rollup-plugin-babel.svg)](https://travis-ci.org/npmtest/node-npmtest-rollup-plugin-babel)

#### Seamless integration between Rollup and Babel.

[![NPM](https://nodei.co/npm/rollup-plugin-babel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rollup-plugin-babel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rollup-plugin-babel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rollup-plugin-babel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/test-report.html](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rollup-plugin-babel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rollup-plugin-babel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rollup-plugin-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rollup-plugin-babel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rollup-plugin-babel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rich Harris"
    },
    "bugs": {
        "url": "https://github.com/rollup/rollup-plugin-babel/issues"
    },
    "contributors": [
        {
            "name": "Bogdan Chadkin"
        }
    ],
    "dependencies": {
        "babel-core": "6",
        "babel-plugin-transform-es2015-classes": "^6.9.0",
        "object-assign": "^4.1.0",
        "rollup-pluginutils": "^1.5.0"
    },
    "description": "Seamless integration between Rollup and Babel.",
    "devDependencies": {
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-es2015-rollup": "^3.0.0",
        "buble": "^0.14.2",
        "eslint": "^3.12.0",
        "mocha": "^3.2.0",
        "rollup": "^0.37.0",
        "rollup-plugin-buble": "^0.14.0",
        "source-map": "^0.5.6",
        "source-map-support": "^0.4.6"
    },
    "directories": {},
    "dist": {
        "shasum": "16528197b0f938a1536f44683c7a93d573182f57",
        "tarball": "https://registry.npmjs.org/rollup-plugin-babel/-/rollup-plugin-babel-2.7.1.tgz"
    },
    "files": [
        "src",
        "dist/rollup-plugin-babel.cjs.js",
        "dist/rollup-plugin-babel.es.js",
        "README"
    ],
    "gitHead": "17d007544fe6764840ea11213af422640e415edd",
    "homepage": "https://github.com/rollup/rollup-plugin-babel",
    "jsnext:main": "dist/rollup-plugin-babel.es.js",
    "keywords": [
        "rollup-plugin",
        "babel",
        "es2015",
        "es6"
    ],
    "license": "MIT",
    "main": "dist/rollup-plugin-babel.cjs.js",
    "maintainers": [
        {
            "name": "eventualbuddha"
        },
        {
            "name": "rich_harris"
        },
        {
            "name": "trysound"
        },
        {
            "name": "victorystick"
        }
    ],
    "name": "rollup-plugin-babel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rollup/rollup-plugin-babel.git"
    },
    "scripts": {
        "build": "rollup -c",
        "lint": "eslint src",
        "prebuild": "rm -rf dist/*",
        "prepublish": "npm run lint && npm test",
        "pretest": "npm run build",
        "test": "mocha"
    },
    "version": "2.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
