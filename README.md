# npmdoc-riot

#### basic api documentation for  [riot (v3.4.3)](http://riotjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-riot.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-riot) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-riot.svg)](https://travis-ci.org/npmdoc/node-npmdoc-riot)

#### A React-like user interface micro-library

[![NPM](https://nodei.co/npm/riot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/riot)

- [https://npmdoc.github.io/node-npmdoc-riot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-riot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-riot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-riot/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-riot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-riot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Riot maintainers team + smart people from all over the world"
    },
    "bin": {
        "riot": "node_modules/riot-cli/lib/index.js"
    },
    "browser": "riot.js",
    "bugs": {
        "url": "https://github.com/riot/riot/issues"
    },
    "contributors": [
        {
            "name": "Richard Bondi https://github.com/rsbondi"
        },
        {
            "name": "Gianluca Guarini https://github.com/GianlucaGuarini"
        },
        {
            "name": "Tsutomu Kawamura https://github.com/cognitom"
        },
        {
            "name": "Alberto Martínez https://github.com/aMarCruz"
        },
        {
            "name": "Grant Marvin     https://github.com/rogueg"
        },
        {
            "name": "Tero Piirainen   https://github.com/tipiirai"
        }
    ],
    "dependencies": {
        "riot-cli": "^3.0.0",
        "riot-compiler": "^3.2.1",
        "riot-observable": "^3.0.0",
        "riot-tmpl": "^3.0.3",
        "simple-dom": "0.3.2",
        "simple-html-tokenizer": "^0.4.1"
    },
    "description": "A React-like user interface micro-library",
    "devDependencies": {
        "benchmark": "^2.1.4",
        "chai": "^3.5.0",
        "cheerio": "^0.22.0",
        "chokidar-cli": "^1.2.0",
        "coveralls": "^2.13.0",
        "eslint": "^3.19.0",
        "glob": "^7.1.1",
        "istanbul": "^0.4.5",
        "jsdom": "^9.12.0",
        "karma": "^1.6.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.4",
        "karma-rollup-preprocessor": "^4.0.0",
        "karma-sauce-launcher": "^1.1.0",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.14",
        "rollup": "^0.41.6",
        "rollup-plugin-alias": "1.2.1",
        "rollup-plugin-buble": "^0.15.0",
        "rollup-plugin-commonjs": "^8.0.2",
        "rollup-plugin-node-resolve": "^3.0.0",
        "rollup-plugin-riot": "^1.1.0",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.9.0",
        "uglify-js": "^2.8.22"
    },
    "directories": {},
    "dist": {
        "shasum": "5a3fd4023d121303b3911d7ab229a1524edc6318",
        "tarball": "https://registry.npmjs.org/riot/-/riot-3.4.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "lib",
        "riot.js",
        "riot.min.js",
        "riot.csp.js",
        "riot.csp.min.js",
        "riot+compiler.js",
        "riot+compiler.min.js"
    ],
    "gitHead": "615c192a38dbe804e2df4af25009f06284c03f42",
    "homepage": "http://riotjs.com/",
    "jsnext:main": "lib/riot.js",
    "keywords": [
        "custom tags",
        "custom elements",
        "web components",
        "virtual dom",
        "shadow dom",
        "polymer",
        "react",
        "jsx",
        "minimal",
        "minimalist",
        "client-side",
        "framework",
        "declarative",
        "templating",
        "template",
        "data binding",
        "mvc",
        "model",
        "view",
        "controller",
        "riotjs",
        "riot.js"
    ],
    "license": "MIT",
    "main": "lib/server/index.js",
    "maintainers": [
        {
            "name": "tipiirai"
        },
        {
            "name": "aurri"
        },
        {
            "name": "gianlucaguarini"
        },
        {
            "name": "cognitom"
        }
    ],
    "module": "lib/riot.js",
    "name": "riot",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/riot/riot.git"
    },
    "scripts": {
        "test": "make riot"
    },
    "version": "3.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
