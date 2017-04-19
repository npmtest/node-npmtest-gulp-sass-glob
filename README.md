# npmtest-gulp-sass-glob

#### basic test coverage for  [gulp-sass-glob (v1.0.8)](https://github.com/tomgrooffer/gulp-sass-glob#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-sass-glob.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-sass-glob) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-sass-glob.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-sass-glob)

#### Gulp task to use glob imports in your sass/scss files.

[![NPM](https://nodei.co/npm/gulp-sass-glob.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-sass-glob)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-sass-glob/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-sass-glob/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-sass-glob/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-sass-glob/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-sass-glob/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-sass-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-sass-glob/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-sass-glob/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Vercoelen"
    },
    "bugs": {
        "url": "https://github.com/tomgrooffer/gulp-sass-glob/issues"
    },
    "dependencies": {
        "glob": "^7.1.1",
        "minimatch": "^3.0.3",
        "slash": "^1.0.0",
        "through2": "^2.0.3"
    },
    "description": "Gulp task to use glob imports in your sass/scss files.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "eslint": "^3.11.1",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-babel": "^4.0.0",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "expect.js": "^0.3.1",
        "husky": "^0.11.9",
        "mocha": "^3.2.0",
        "vinyl-fs": "^2.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "3b737ecebc9e6c106b82574c6faa9314bd94aeaa",
        "tarball": "https://registry.npmjs.org/gulp-sass-glob/-/gulp-sass-glob-1.0.8.tgz"
    },
    "gitHead": "13562a52ea2e496af1ac126b39dbfdc18fd8113f",
    "homepage": "https://github.com/tomgrooffer/gulp-sass-glob#readme",
    "keywords": [
        "gulp",
        "sass",
        "glob",
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "mikevercoelen"
        }
    ],
    "name": "gulp-sass-glob",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://tomgrooffer@github.com/tomgrooffer/gulp-sass-glob.git"
    },
    "scripts": {
        "compile": "babel -d dist/ src/",
        "lint": "eslint .",
        "lint-fix": "eslint . --fix",
        "prepublish": "npm run compile",
        "prepush": "npm run lint && npm run test",
        "start": "npm run compile && node dist/index.js",
        "test": "mocha --compilers js:babel-register"
    },
    "version": "1.0.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
