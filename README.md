# npmdoc-babel-plugin-macros

#### api documentation for  [babel-plugin-macros (v1.0.15)](https://github.com/codemix/babel-plugin-macros)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-plugin-macros.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-plugin-macros) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-plugin-macros.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-plugin-macros)

#### Macros for JavaScript via a babel plugin.

[![NPM](https://nodei.co/npm/babel-plugin-macros.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-macros)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-plugin-macros/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "babel-plugin-macros",
    "version": "1.0.15",
    "description": "Macros for JavaScript via a babel plugin.",
    "main": "lib/index.js",
    "scripts": {
        "build": "babel -d ./lib ./src",
        "prepublish": "npm run test",
        "pretest": "npm run build && npm run lint",
        "test": "mocha",
        "watch": "mocha --watch",
        "lint": "eslint **/*.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/codemix/babel-plugin-macros"
    },
    "keywords": [
        "babel",
        "babel-plugin",
        "macros",
        "ast"
    ],
    "author": "Charles Pick <charles@codemix.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/codemix/babel-plugin-macros/issues"
    },
    "homepage": "https://github.com/codemix/babel-plugin-macros",
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.2",
        "babel-eslint": "^4.1.6",
        "babel-plugin-transform-flow-strip-types": "^6.5.0",
        "babel-plugin-typecheck": "^3.6.1",
        "babel-preset-es2015": "^6.5.0",
        "babel-register": "^6.5.2",
        "eslint": "^1.10.3",
        "mocha": "^2.4.5",
        "should": "^8.2.2"
    },
    "dependencies": {
        "babel-traverse": "^6.5.0",
        "babel-types": "^6.5.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
