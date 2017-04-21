# npmdoc-karma-jspm

#### api documentation for  [karma-jspm (v2.2.3)](https://github.com/Workiva/karma-jspm#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-jspm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-jspm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-jspm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-jspm)

#### Include jspm module loader for karma runs; allows dynamic loading of src and test files and modules

[![NPM](https://nodei.co/npm/karma-jspm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-jspm)

- [https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Max Peterson"
    },
    "bugs": {
        "url": "https://github.com/Workiva/karma-jspm/issues"
    },
    "contributors": [
        {
            "name": "Max Peterson"
        }
    ],
    "dependencies": {
        "glob": "~7.0.5"
    },
    "description": "Include jspm module loader for karma runs; allows dynamic loading of src and test files and modules",
    "devDependencies": {
        "cross-env": "^1.0.7",
        "eslint": "^2.10.2",
        "jasmine": "^2.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "bb15cd0c8c0902480113d39620215704159d5503",
        "tarball": "https://registry.npmjs.org/karma-jspm/-/karma-jspm-2.2.3.tgz"
    },
    "gitHead": "4e5f47b0977a8c6adb74707c662240e49c42f3f5",
    "homepage": "https://github.com/Workiva/karma-jspm#readme",
    "keywords": [
        "karma-plugin",
        "karma-adapter",
        "jspm"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bitcollage"
        },
        {
            "name": "computmaxer"
        }
    ],
    "name": "karma-jspm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Workiva/karma-jspm.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "cross-env JASMINE_CONFIG_PATH=test/jasmine.json jasmine 'test/**/*.spec.js'"
    },
    "version": "2.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
