# npmtest-modify-babel-preset

#### basic test coverage for  [modify-babel-preset (v3.2.1)](https://github.com/developit/modify-babel-preset#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-modify-babel-preset.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-modify-babel-preset) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-modify-babel-preset.svg)](https://travis-ci.org/npmtest/node-npmtest-modify-babel-preset)

#### Create a modified babel preset based on an an existing preset.

[![NPM](https://nodei.co/npm/modify-babel-preset.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/modify-babel-preset)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-modify-babel-preset/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-modify-babel-preset/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-modify-babel-preset/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-modify-babel-preset/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-modify-babel-preset/build/test-report.html](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-modify-babel-preset/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Miller"
    },
    "bugs": {
        "url": "https://github.com/developit/modify-babel-preset/issues"
    },
    "dependencies": {
        "require-relative": "^0.8.7"
    },
    "description": "Create a modified babel preset based on an an existing preset.",
    "devDependencies": {
        "babel-plugin-transform-react-jsx": "^6.8.0",
        "babel-preset-es2015": "^6.9.0",
        "chai": "^3.5.0",
        "cross-env": "^2.0.0",
        "mocha": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "d7172aa3c0822ed3fc08e308fd0971295136ab50",
        "tarball": "https://registry.npmjs.org/modify-babel-preset/-/modify-babel-preset-3.2.1.tgz"
    },
    "gitHead": "bcdd07c2cc624f1cff30e5401b9c92b86c96a4e8",
    "homepage": "https://github.com/developit/modify-babel-preset#readme",
    "keywords": [
        "babel",
        "preset"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "developit"
        }
    ],
    "name": "modify-babel-preset",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/developit/modify-babel-preset.git"
    },
    "scripts": {
        "prepublish": "cross-env NODE_ENV=development npm test",
        "pretest": "cd test/fixtures/two/node_modules/one && npm i",
        "release": "git commit -am $npm_package_version && git tag $npm_package_version && git push && git push --tags && npm publish",
        "test": "mocha test/*.js"
    },
    "version": "3.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
