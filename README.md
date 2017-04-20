# npmtest-color-namer

#### basic test coverage for  [color-namer (v1.1.0)](https://github.com/zeke/color-namer)  [![npm package](https://img.shields.io/npm/v/npmtest-color-namer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-color-namer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-color-namer.svg)](https://travis-ci.org/npmtest/node-npmtest-color-namer)

#### Give me a color and I'll name it.

[![NPM](https://nodei.co/npm/color-namer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/color-namer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-color-namer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-color-namer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-color-namer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-color-namer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-color-namer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-color-namer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-color-namer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-color-namer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-color-namer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-color-namer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-color-namer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-color-namer/build/test-report.html](https://npmtest.github.io/node-npmtest-color-namer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-color-namer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-color-namer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-color-namer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-color-namer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-color-namer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zeke Sikelianos",
        "url": "http://zeke.sikelianos.com/"
    },
    "bugs": {
        "url": "https://github.com/zeke/color-namer/issues"
    },
    "dependencies": {
        "chroma-js": "~0.5.2",
        "euclidean-distance": "~0.1.0"
    },
    "description": "Give me a color and I'll name it.",
    "devDependencies": {
        "browserify": "^4.2.1",
        "mocha": "~1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1338ba293d2288ba40cf649df28d0712f8830074",
        "tarball": "https://registry.npmjs.org/color-namer/-/color-namer-1.1.0.tgz"
    },
    "gitHead": "cc587083a29c29dfa5b4c89b95357f2fe9aae883",
    "homepage": "https://github.com/zeke/color-namer",
    "keywords": [
        "color",
        "colors",
        "names",
        "rgb",
        "hsl",
        "hsv",
        "lab",
        "search",
        "tagging",
        "image",
        "design"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zeke"
        }
    ],
    "name": "color-namer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/zeke/color-namer.git"
    },
    "scripts": {
        "build": "browserify index.js --standalone colorNamer > dist/color-namer.js",
        "test": "mocha"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
