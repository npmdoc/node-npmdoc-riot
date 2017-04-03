# api documentation for  [riot (v3.4.0)](http://riotjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-riot.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-riot) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-riot.svg)](https://travis-ci.org/npmdoc/node-npmdoc-riot)
#### A React-like user interface micro-library

[![NPM](https://nodei.co/npm/riot.png?downloads=true)](https://www.npmjs.com/package/riot)

[![apidoc](https://npmdoc.github.io/node-npmdoc-riot/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-riot_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-riot/build/apidoc.html)

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
        "simple-html-tokenizer": "^0.4.0"
    },
    "description": "A React-like user interface micro-library",
    "devDependencies": {
        "benchmark": "^2.1.3",
        "chai": "^3.5.0",
        "cheerio": "^0.22.0",
        "chokidar-cli": "^1.2.0",
        "coveralls": "^2.12.0",
        "eslint": "^3.18.0",
        "glob": "^7.1.1",
        "istanbul": "^0.4.5",
        "jsdom": "^9.12.0",
        "karma": "^1.5.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.4",
        "karma-rollup-preprocessor": "^3.0.3",
        "karma-sauce-launcher": "^1.1.0",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.14",
        "rollup": "^0.41.6",
        "rollup-plugin-alias": "^1.2.1",
        "rollup-plugin-buble": "^0.15.0",
        "rollup-plugin-commonjs": "^8.0.2",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-riot": "^1.1.0",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.9.0",
        "uglify-js": "^2.8.14"
    },
    "directories": {},
    "dist": {
        "shasum": "ef61999ec9d821f1fd150509c966d6650ffc08e6",
        "tarball": "https://registry.npmjs.org/riot/-/riot-3.4.0.tgz"
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
    "gitHead": "a744e01215e394389a2fb71c04fc0e007d118f9a",
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
            "name": "tipiirai",
            "email": "tero@muut.com"
        },
        {
            "name": "aurri",
            "email": "au@rim.as"
        },
        {
            "name": "gianlucaguarini",
            "email": "gianluca.guarini@gmail.com"
        },
        {
            "name": "cognitom",
            "email": "kawamura@cognitom.com"
        }
    ],
    "module": "lib/riot.js",
    "name": "riot",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/riot/riot.git"
    },
    "scripts": {
        "test": "make riot"
    },
    "version": "3.4.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module riot](#apidoc.module.riot)
1.  [function <span class="apidocSignatureSpan">riot.</span>Tag (el, opts)](#apidoc.element.riot.Tag)
1.  [function <span class="apidocSignatureSpan">riot.</span>compile (src, opts, url)](#apidoc.element.riot.compile)
1.  [function <span class="apidocSignatureSpan">riot.</span>mixin (name, mix, g)](#apidoc.element.riot.mixin)
1.  [function <span class="apidocSignatureSpan">riot.</span>mount (selector, tagName, opts)](#apidoc.element.riot.mount)
1.  [function <span class="apidocSignatureSpan">riot.</span>observable (el)](#apidoc.element.riot.observable)
1.  [function <span class="apidocSignatureSpan">riot.</span>render (tagName, opts)](#apidoc.element.riot.render)
1.  [function <span class="apidocSignatureSpan">riot.</span>renderAsync (tagName, opts)](#apidoc.element.riot.renderAsync)
1.  [function <span class="apidocSignatureSpan">riot.</span>require (filename, opts)](#apidoc.element.riot.require)
1.  [function <span class="apidocSignatureSpan">riot.</span>tag (name, tmpl, css, attrs, fn)](#apidoc.element.riot.tag)
1.  [function <span class="apidocSignatureSpan">riot.</span>tag2 (name, tmpl, css, attrs, fn)](#apidoc.element.riot.tag2)
1.  [function <span class="apidocSignatureSpan">riot.</span>unregister (name)](#apidoc.element.riot.unregister)
1.  [function <span class="apidocSignatureSpan">riot.</span>update ()](#apidoc.element.riot.update)
1.  [function <span class="apidocSignatureSpan">riot.</span>util.brackets (reOrIdx)](#apidoc.element.riot.util.brackets)
1.  [function <span class="apidocSignatureSpan">riot.</span>util.tmpl (str, data)](#apidoc.element.riot.util.tmpl)
1.  object <span class="apidocSignatureSpan">riot.</span>parsers
1.  object <span class="apidocSignatureSpan">riot.</span>parsers.css
1.  object <span class="apidocSignatureSpan">riot.</span>parsers.html
1.  object <span class="apidocSignatureSpan">riot.</span>parsers.js
1.  object <span class="apidocSignatureSpan">riot.</span>riot_csp
1.  object <span class="apidocSignatureSpan">riot.</span>settings
1.  object <span class="apidocSignatureSpan">riot.</span>util
1.  object <span class="apidocSignatureSpan">riot.</span>util.check
1.  object <span class="apidocSignatureSpan">riot.</span>util.dom
1.  object <span class="apidocSignatureSpan">riot.</span>util.misc
1.  object <span class="apidocSignatureSpan">riot.</span>util.styleManager
1.  object <span class="apidocSignatureSpan">riot.</span>util.tags
1.  string <span class="apidocSignatureSpan">riot.</span>version

#### [module riot.parsers](#apidoc.module.riot.parsers)
1.  [function <span class="apidocSignatureSpan">riot.parsers.</span>_req (name, req)](#apidoc.element.riot.parsers._req)
1.  object <span class="apidocSignatureSpan">riot.parsers.</span>css
1.  object <span class="apidocSignatureSpan">riot.parsers.</span>html
1.  object <span class="apidocSignatureSpan">riot.parsers.</span>js

#### [module riot.parsers.css](#apidoc.module.riot.parsers.css)
1.  [function <span class="apidocSignatureSpan">riot.parsers.css.</span>less (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.less)
1.  [function <span class="apidocSignatureSpan">riot.parsers.css.</span>sass (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.sass)
1.  [function <span class="apidocSignatureSpan">riot.parsers.css.</span>scss (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.scss)
1.  [function <span class="apidocSignatureSpan">riot.parsers.css.</span>stylus (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.stylus)

#### [module riot.parsers.html](#apidoc.module.riot.parsers.html)
1.  [function <span class="apidocSignatureSpan">riot.parsers.html.</span>jade (p1, p2, p3, p4)](#apidoc.element.riot.parsers.html.jade)
1.  [function <span class="apidocSignatureSpan">riot.parsers.html.</span>pug (p1, p2, p3, p4)](#apidoc.element.riot.parsers.html.pug)

#### [module riot.parsers.js](#apidoc.module.riot.parsers.js)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>buble (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.buble)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>coffee (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.coffee)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>coffeescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.coffeescript)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>es6 (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.es6)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>javascript (src)](#apidoc.element.riot.parsers.js.javascript)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>livescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.livescript)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>none (src)](#apidoc.element.riot.parsers.js.none)
1.  [function <span class="apidocSignatureSpan">riot.parsers.js.</span>typescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.typescript)

#### [module riot.render](#apidoc.module.riot.render)
1.  [function <span class="apidocSignatureSpan">riot.</span>render (tagName, opts)](#apidoc.element.riot.render.render)
1.  [function <span class="apidocSignatureSpan">riot.render.</span>dom (tagName, opts)](#apidoc.element.riot.render.dom)
1.  [function <span class="apidocSignatureSpan">riot.render.</span>tag (tagName, opts)](#apidoc.element.riot.render.tag)

#### [module riot.riot_csp](#apidoc.module.riot.riot_csp)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>Tag (el, opts)](#apidoc.element.riot.riot_csp.Tag)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>mixin (name, mix, g)](#apidoc.element.riot.riot_csp.mixin)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>mount (selector, tagName, opts)](#apidoc.element.riot.riot_csp.mount)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>observable (el)](#apidoc.element.riot.riot_csp.observable)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>tag (name, tmpl, css, attrs, fn)](#apidoc.element.riot.riot_csp.tag)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>tag2 (name, tmpl, css, attrs, fn)](#apidoc.element.riot.riot_csp.tag2)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>unregister (name)](#apidoc.element.riot.riot_csp.unregister)
1.  [function <span class="apidocSignatureSpan">riot.riot_csp.</span>update ()](#apidoc.element.riot.riot_csp.update)
1.  object <span class="apidocSignatureSpan">riot.riot_csp.</span>default
1.  object <span class="apidocSignatureSpan">riot.riot_csp.</span>settings
1.  object <span class="apidocSignatureSpan">riot.riot_csp.</span>util
1.  string <span class="apidocSignatureSpan">riot.riot_csp.</span>version

#### [module riot.util](#apidoc.module.riot.util)
1.  [function <span class="apidocSignatureSpan">riot.util.</span>brackets (reOrIdx)](#apidoc.element.riot.util.brackets)
1.  [function <span class="apidocSignatureSpan">riot.util.</span>tmpl (str, data)](#apidoc.element.riot.util.tmpl)
1.  object <span class="apidocSignatureSpan">riot.util.</span>check
1.  object <span class="apidocSignatureSpan">riot.util.</span>dom
1.  object <span class="apidocSignatureSpan">riot.util.</span>misc
1.  object <span class="apidocSignatureSpan">riot.util.</span>styleManager
1.  object <span class="apidocSignatureSpan">riot.util.</span>tags
1.  object <span class="apidocSignatureSpan">riot.util.</span>vdom

#### [module riot.util.brackets](#apidoc.module.riot.util.brackets)
1.  [function <span class="apidocSignatureSpan">riot.util.</span>brackets (reOrIdx)](#apidoc.element.riot.util.brackets.brackets)
1.  [function <span class="apidocSignatureSpan">riot.util.brackets.</span>array (pair)](#apidoc.element.riot.util.brackets.array)
1.  [function <span class="apidocSignatureSpan">riot.util.brackets.</span>hasExpr (str)](#apidoc.element.riot.util.brackets.hasExpr)
1.  [function <span class="apidocSignatureSpan">riot.util.brackets.</span>loopKeys (expr)](#apidoc.element.riot.util.brackets.loopKeys)
1.  [function <span class="apidocSignatureSpan">riot.util.brackets.</span>set (pair)](#apidoc.element.riot.util.brackets.set)
1.  [function <span class="apidocSignatureSpan">riot.util.brackets.</span>split (str, tmpl, _bp)](#apidoc.element.riot.util.brackets.split)
1.  object <span class="apidocSignatureSpan">riot.util.brackets.</span>R_MLCOMMS
1.  object <span class="apidocSignatureSpan">riot.util.brackets.</span>R_STRINGS
1.  string <span class="apidocSignatureSpan">riot.util.brackets.</span>S_QBLOCKS
1.  string <span class="apidocSignatureSpan">riot.util.brackets.</span>version

#### [module riot.util.check](#apidoc.module.riot.util.check)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isArray (value)](#apidoc.element.riot.util.check.isArray)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isBlank (value)](#apidoc.element.riot.util.check.isBlank)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isBoolAttr (value)](#apidoc.element.riot.util.check.isBoolAttr)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isFunction (value)](#apidoc.element.riot.util.check.isFunction)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isObject (value)](#apidoc.element.riot.util.check.isObject)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isReservedName (value)](#apidoc.element.riot.util.check.isReservedName)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isString (value)](#apidoc.element.riot.util.check.isString)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isUndefined (value)](#apidoc.element.riot.util.check.isUndefined)
1.  [function <span class="apidocSignatureSpan">riot.util.check.</span>isWritable (obj, key)](#apidoc.element.riot.util.check.isWritable)

#### [module riot.util.dom](#apidoc.module.riot.util.dom)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>createDOMPlaceholder ()](#apidoc.element.riot.util.dom.createDOMPlaceholder)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>createFrag ()](#apidoc.element.riot.util.dom.createFrag)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>getAttr (dom, name)](#apidoc.element.riot.util.dom.getAttr)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>mkEl (name)](#apidoc.element.riot.util.dom.mkEl)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>remAttr (dom, name)](#apidoc.element.riot.util.dom.remAttr)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>safeInsert (root, curr, next)](#apidoc.element.riot.util.dom.safeInsert)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>setAttr (dom, name, val)](#apidoc.element.riot.util.dom.setAttr)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>setInnerHTML (container, html)](#apidoc.element.riot.util.dom.setInnerHTML)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>styleObjectToString (style)](#apidoc.element.riot.util.dom.styleObjectToString)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>toggleVisibility (dom, show)](#apidoc.element.riot.util.dom.toggleVisibility)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>walkAttrs (html, fn)](#apidoc.element.riot.util.dom.walkAttrs)
1.  [function <span class="apidocSignatureSpan">riot.util.dom.</span>walkNodes (dom, fn, context)](#apidoc.element.riot.util.dom.walkNodes)

#### [module riot.util.misc](#apidoc.module.riot.util.misc)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>contains (array, item)](#apidoc.element.riot.util.misc.contains)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>defineProperty (el, key, value, options)](#apidoc.element.riot.util.misc.defineProperty)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>each (list, fn)](#apidoc.element.riot.util.misc.each)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>extend (src)](#apidoc.element.riot.util.misc.extend)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>startsWith (str, value)](#apidoc.element.riot.util.misc.startsWith)
1.  [function <span class="apidocSignatureSpan">riot.util.misc.</span>toCamel (str)](#apidoc.element.riot.util.misc.toCamel)

#### [module riot.util.styleManager](#apidoc.module.riot.util.styleManager)
1.  [function <span class="apidocSignatureSpan">riot.util.styleManager.</span>add (css, name)](#apidoc.element.riot.util.styleManager.add)
1.  [function <span class="apidocSignatureSpan">riot.util.styleManager.</span>inject ()](#apidoc.element.riot.util.styleManager.inject)

#### [module riot.util.tags](#apidoc.module.riot.util.tags)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>arrayishAdd (obj, key, value, ensureArray, index)](#apidoc.element.riot.util.tags.arrayishAdd)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>arrayishRemove (obj, key, value, ensureArray)](#apidoc.element.riot.util.tags.arrayishRemove)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>cleanUpData (data)](#apidoc.element.riot.util.tags.cleanUpData)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>getImmediateCustomParentTag (tag)](#apidoc.element.riot.util.tags.getImmediateCustomParentTag)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>getTag (dom)](#apidoc.element.riot.util.tags.getTag)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>getTagName (dom, skipDataIs)](#apidoc.element.riot.util.tags.getTagName)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>inheritFrom (target, propsInSyncWithParent)](#apidoc.element.riot.util.tags.inheritFrom)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>initChildTag (child, opts, innerHTML, parent)](#apidoc.element.riot.util.tags.initChildTag)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>makeReplaceVirtual (tag, ref)](#apidoc.element.riot.util.tags.makeReplaceVirtual)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>makeVirtual (src, target)](#apidoc.element.riot.util.tags.makeVirtual)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>mountTo (root, tagName, opts, ctx)](#apidoc.element.riot.util.tags.mountTo)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>moveChildTag (tagName, newPos)](#apidoc.element.riot.util.tags.moveChildTag)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>moveVirtual (src, target)](#apidoc.element.riot.util.tags.moveVirtual)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>selectTags (tags)](#apidoc.element.riot.util.tags.selectTags)
1.  [function <span class="apidocSignatureSpan">riot.util.tags.</span>unmountAll (expressions)](#apidoc.element.riot.util.tags.unmountAll)

#### [module riot.util.tmpl](#apidoc.module.riot.util.tmpl)
1.  [function <span class="apidocSignatureSpan">riot.util.</span>tmpl (str, data)](#apidoc.element.riot.util.tmpl.tmpl)
1.  [function <span class="apidocSignatureSpan">riot.util.tmpl.</span>clearCache ()](#apidoc.element.riot.util.tmpl.clearCache)
1.  [function <span class="apidocSignatureSpan">riot.util.tmpl.</span>hasExpr (str)](#apidoc.element.riot.util.tmpl.hasExpr)
1.  [function <span class="apidocSignatureSpan">riot.util.tmpl.</span>loopKeys (expr)](#apidoc.element.riot.util.tmpl.loopKeys)
1.  object <span class="apidocSignatureSpan">riot.util.tmpl.</span>errorHandler
1.  string <span class="apidocSignatureSpan">riot.util.tmpl.</span>version



# <a name="apidoc.module.riot"></a>[module riot](#apidoc.module.riot)

#### <a name="apidoc.element.riot.Tag"></a>[function <span class="apidocSignatureSpan">riot.</span>Tag (el, opts)](#apidoc.element.riot.Tag)
- description and source-code
```javascript
function Tag$2(el, opts) {
  // get the tag properties from the class constructor
  var ref = this;
  var name = ref.name;
  var tmpl = ref.tmpl;
  var css = ref.css;
  var attrs = ref.attrs;
  var onCreate = ref.onCreate;
  // register a new tag and cache the class prototype
  if (!__TAG_IMPL[name]) {
    tag$1(name, tmpl, css, attrs, onCreate);
    // cache the class constructor
    __TAG_IMPL[name].class = this.constructor;
  }

  // mount the tag using the class instance
  mountTo(el, name, opts, this);
  // inject the component css
  if (css) { styleManager.inject(); }

  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.compile"></a>[function <span class="apidocSignatureSpan">riot.</span>compile (src, opts, url)](#apidoc.element.riot.compile)
- description and source-code
```javascript
function compile(src, opts, url) {
  var
    parts = [],
    included,
    defaultParserptions = {

      template: {},
      js: {},
      style: {}
    }

  if (!opts) opts = {}

  opts.parserOptions = extend(defaultParserptions, opts.parserOptions || {})

  included = opts.exclude
    ? function (s) { return opts.exclude.indexOf(s) < 0 } : function () { return 1 }

  if (!url) url = process.cwd() + '/.'

  var _bp = brackets.array(opts.brackets)

  if (opts.template) {
    src = compileTemplate(src, url, opts.template, opts.parserOptions.template)
  }

  src = cleanSource(src)
    .replace(CUST_TAG, function (_, indent, tagName, attribs, body, body2) {
      var
        jscode = '',
        styles = '',
        html = '',
        imports = '',
        pcex = []

      pcex._bp = _bp

      tagName = tagName.toLowerCase()

      attribs = attribs && included('attribs')
        ? restoreExpr(
            parseAttribs(
              splitHtml(attribs, opts, pcex),
            pcex),
          pcex) : ''

      if ((body || (body = body2)) && /\S/.test(body)) {

        if (body2) {

          if (included('html')) html = _compileHTML(body2, opts, pcex)
        } else {

          body = body.replace(RegExp('^' + indent, 'gm'), '')

          body = body.replace(SCRIPTS, function (_m, _attrs, _script) {
            if (included('js')) {
              var code = getCode(_script, opts, _attrs, url)

              if (code === false) return _m.replace(DEFER_ATTR, '')
              if (code) jscode += (jscode ? '\n' : '') + code
            }
            return ''
          })

          body = body.replace(STYLES, function (_m, _attrs, _style) {
            if (included('css')) {
              styles += (styles ? ' ' : '') + cssCode(_style, opts, _attrs, url, tagName)
            }
            return ''
          })

          var blocks = splitBlocks(body.replace(TRIM_TRAIL, ''))

          if (included('html')) {
            html = _compileHTML(blocks[0], opts, pcex)
          }

          if (included('js')) {
            body = _compileJS(blocks[1], opts, null, null, url)
            if (body) jscode += (jscode ? '\n' : '') + body
            jscode = jscode.replace(IMPORT_STATEMENT, function (s) {
              imports += s.trim() + '\n'
              return ''
            })
          }
        }
      }

      jscode = /\S/.test(jscode) ? jscode.replace(/\n{3,}/g, '\n\n') : ''

      if (opts.entities) {
        parts.push({
          tagName: tagName,
          html: html,
          css: styles,
          attribs: attribs,
          js: jscode,
          imports: imports
        })
        return ''
      }

      return mktag(tagName, html, styles, attribs, jscode, imports, opts)
    })

  if (opts.entities) return parts

  if (opts.debug && url.slice(-2) !== '/.') {
    if (/^[\\/]/.test(url)) url = path.relative('.', url)
    src = '//src: ' + url.replace(/\\/g, '/') + '\n' + src
  }
  return src
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.mixin"></a>[function <span class="apidocSignatureSpan">riot.</span>mixin (name, mix, g)](#apidoc.element.riot.mixin)
- description and source-code
```javascript
function mixin$1(name, mix, g) {
  // Unnamed global
  if (isObject(name)) {
    mixin$1(("__unnamed_" + (mixins_id++)), name, true);
    return
  }

  var store = g ? globals : mixins;

  // Getter
  if (!mix) {
    if (isUndefined(store[name]))
      { throw new Error('Unregistered mixin: ' + name) }

    return store[name]
  }

  // Setter
  store[name] = isFunction(mix) ?
    extend(mix.prototype, store[name] || {}) && mix :
    extend(store[name] || {}, mix);
}
```
- example usage
```shell
...

// add global mixins
var globalMixin = mixin$1(GLOBAL_MIXIN);

if (globalMixin && !skipAnonymous) {
  for (var i in globalMixin) {
    if (globalMixin.hasOwnProperty(i)) {
      this$1.mixin(globalMixin[i]);
    }
  }
}

if (impl.fn) { impl.fn.call(this, opts); }

if (!skipAnonymous) { this.trigger('before-mount'); }
...
```

#### <a name="apidoc.element.riot.mount"></a>[function <span class="apidocSignatureSpan">riot.</span>mount (selector, tagName, opts)](#apidoc.element.riot.mount)
- description and source-code
```javascript
function mount$1(selector, tagName, opts) {
  var tags = [];

  function pushTagsTo(root) {
    if (root.tagName) {
      var riotTag = getAttr(root, IS_DIRECTIVE);

      // have tagName? force riot-tag to be the same
      if (tagName && riotTag !== tagName) {
        riotTag = tagName;
        setAttr(root, IS_DIRECTIVE, tagName);
      }

      var tag = mountTo(root, riotTag || root.tagName.toLowerCase(), opts);

      if (tag)
        { tags.push(tag); }
    } else if (root.length)
      { each(root, pushTagsTo); } // assume nodeList
  }

  // inject styles into DOM
  styleManager.inject();

  if (isObject(tagName)) {
    opts = tagName;
    tagName = 0;
  }

  var elem;
  var allTags;

  // crawl the DOM to find the tag
  if (isString(selector)) {
    selector = selector === '*' ?
      // select all registered tags
      // & tags found with the riot-tag attribute set
      allTags = selectTags() :
      // or just the ones named like the selector
      selector + selectTags(selector.split(/, */));

    // make sure to pass always a selector
    // to the querySelectorAll function
    elem = selector ? $$(selector) : [];
  }
  else
    // probably you have passed already a tag or a NodeList
    { elem = selector; }

  // select all the registered and mount them inside their root elements
  if (tagName === '*') {
    // get all custom tags
    tagName = allTags || selectTags();
    // if the root els it's just a single tag
    if (elem.tagName)
      { elem = $$(tagName, elem); }
    else {
      // select all the children for all the different root elements
      var nodeList = [];

      each(elem, function (_el) { return nodeList.push($$(tagName, _el)); });

      elem = nodeList;
    }
    // get rid of the tagName
    tagName = 0;
  }

  pushTagsTo(elem);

  return tags
}
```
- example usage
```shell
...
'''

[Open this example on Plunker](http://riotjs.com/examples/plunker/?app=timer)

#### Mounting

''' javascript
riot.mount('timer', { start: 0 })
'''

#### Nesting

Custom tags lets you build complex views with HTML.

''' html
...
```

#### <a name="apidoc.element.riot.observable"></a>[function <span class="apidocSignatureSpan">riot.</span>observable (el)](#apidoc.element.riot.observable)
- description and source-code
```javascript
observable = function (el) {

<span class="apidocCodeCommentSpan">  /**
   * Extend the original object or create a new empty one
   * @type { Object }
   */
</span>
  el = el || {};

  /**
   * Private variables
   */
  var callbacks = {},
    slice = Array.prototype.slice;

  /**
   * Public Api
   */

  // extend the el object adding the observable methods
  Object.defineProperties(el, {
    /**
     * Listen to the given 'event' ands
     * execute the 'callback' each time an event is triggered.
     * @param  { String } event - event id
     * @param  { Function } fn - callback function
     * @returns { Object } el
     */
    on: {
      value: function(event, fn) {
        if (typeof fn == 'function')
          { (callbacks[event] = callbacks[event] || []).push(fn); }
        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Removes the given 'event' listeners
     * @param   { String } event - event id
     * @param   { Function } fn - callback function
     * @returns { Object } el
     */
    off: {
      value: function(event, fn) {
        if (event == '*' && !fn) { callbacks = {}; }
        else {
          if (fn) {
            var arr = callbacks[event];
            for (var i = 0, cb; cb = arr && arr[i]; ++i) {
              if (cb == fn) { arr.splice(i--, 1); }
            }
          } else { delete callbacks[event]; }
        }
        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Listen to the given 'event' and
     * execute the 'callback' at most once
     * @param   { String } event - event id
     * @param   { Function } fn - callback function
     * @returns { Object } el
     */
    one: {
      value: function(event, fn) {
        function on() {
          el.off(event, on);
          fn.apply(el, arguments);
        }
        return el.on(event, on)
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Execute all callback functions that listen to
     * the given 'event'
     * @param   { String } event - event id
     * @returns { Object } el
     */
    trigger: {
      value: function(event) {
        var arguments$1 = arguments;


        // getting the arguments
        var arglen = arguments.length - 1,
          args = new Array(arglen),
          fns,
          fn,
          i;

        for (i = 0; i < arglen; i++) {
          args[i] = arguments$1[i + 1]; // skip first argument
        }

        fns = slice.call(callbacks[event] || [], 0);

        for (i = 0; fn = fns[i]; ++i) {
          fn.apply(el, args);
        }

        if (callbacks['*'] && event != '*')
          { el.trigger.apply(el, ['*', event].concat(args)); }

        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    }
  });

  return el

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.render"></a>[function <span class="apidocSignatureSpan">riot.</span>render (tagName, opts)](#apidoc.element.riot.render)
- description and source-code
```javascript
function render(tagName, opts) {
  var tag = render.tag(tagName, opts),
    html = getTagHtml(tag)
  // unmount the tag avoiding memory leaks
  tag.unmount()
  return html
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.renderAsync"></a>[function <span class="apidocSignatureSpan">riot.</span>renderAsync (tagName, opts)](#apidoc.element.riot.renderAsync)
- description and source-code
```javascript
function renderAsync(tagName, opts) {
  return Promise.race([
    new Promise((resolve, reject) => {
      setTimeout(function() {
        reject(new Error('Timeout error:: the tag "${ tagName }" didn\'t trigger the "ready" event during the rendering process'))
      }, riot.settings.asyncRenderTimeout)
    }),
    new Promise(resolve => {
      var tag = render.tag(tagName, opts)
      tag.on('ready', function() {
        var html = getTagHtml(tag)
        tag.unmount()
        resolve(html)
      })
    })
  ])
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.require"></a>[function <span class="apidocSignatureSpan">riot.</span>require (filename, opts)](#apidoc.element.riot.require)
- description and source-code
```javascript
function riotRequire(filename, opts) {
  var module = new Module()
  module.id = module.filename = filename
  loadAndCompile(filename, opts, module)
  return module.exports
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.tag"></a>[function <span class="apidocSignatureSpan">riot.</span>tag (name, tmpl, css, attrs, fn)](#apidoc.element.riot.tag)
- description and source-code
```javascript
function tag$1(name, tmpl, css, attrs, fn) {
  if (isFunction(attrs)) {
    fn = attrs;

    if (/^[\w\-]+\s?=/.test(css)) {
      attrs = css;
      css = '';
    } else
      { attrs = ''; }
  }

  if (css) {
    if (isFunction(css))
      { fn = css; }
    else
      { styleManager.add(css); }
  }

  name = name.toLowerCase();
  __TAG_IMPL[name] = { name: name, tmpl: tmpl, attrs: attrs, fn: fn };

  return name
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.tag2"></a>[function <span class="apidocSignatureSpan">riot.</span>tag2 (name, tmpl, css, attrs, fn)](#apidoc.element.riot.tag2)
- description and source-code
```javascript
function tag2$1(name, tmpl, css, attrs, fn) {
  if (css) { styleManager.add(css, name); }

  __TAG_IMPL[name] = { name: name, tmpl: tmpl, attrs: attrs, fn: fn };

  return name
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.unregister"></a>[function <span class="apidocSignatureSpan">riot.</span>unregister (name)](#apidoc.element.riot.unregister)
- description and source-code
```javascript
function unregister$1(name) {
  delete __TAG_IMPL[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.update"></a>[function <span class="apidocSignatureSpan">riot.</span>update ()](#apidoc.element.riot.update)
- description and source-code
```javascript
function update$1() {
  return each(__TAGS_CACHE, function (tag) { return tag.update(); })
}
```
- example usage
```shell
...
<timer>

<p>Seconds Elapsed: { time }</p>

this.time = opts.start || 0

tick() {
  this.update({ time: ++this.time })
}

var timer = setInterval(this.tick, 1000)

this.on('unmount', function() {
  clearInterval(timer)
})
...
```

#### <a name="apidoc.element.riot.util.brackets"></a>[function <span class="apidocSignatureSpan">riot.</span>util.brackets (reOrIdx)](#apidoc.element.riot.util.brackets)
- description and source-code
```javascript
function _brackets(reOrIdx) {
  return reOrIdx instanceof RegExp ? _regex(reOrIdx) : _cache[reOrIdx]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tmpl"></a>[function <span class="apidocSignatureSpan">riot.</span>util.tmpl (str, data)](#apidoc.element.riot.util.tmpl)
- description and source-code
```javascript
function _tmpl(str, data) {
  if (!str) { return str }

  return (_cache[str] || (_cache[str] = _create(str))).call(data, _logErr)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.parsers"></a>[module riot.parsers](#apidoc.module.riot.parsers)

#### <a name="apidoc.element.riot.parsers._req"></a>[function <span class="apidocSignatureSpan">riot.parsers.</span>_req (name, req)](#apidoc.element.riot.parsers._req)
- description and source-code
```javascript
function _req(name, req) {
  var
    err,
    mod,
    branch,
    parser = name.split('.')

  if (parser.length > 1) {
    branch = parser[0]
    parser = parser[1]
  } else {
    branch = NULL
    parser = name
  }

  // is the parser registered?
  branch = _find(branch, parser)
  if (!branch) {
    if (req) {
      err = 'Riot parser "' + name + '" is not registered.'
      throw new Error(err)
    }
    return NULL
  }

  // parser registered, needs load?
  if (_loaders[branch][parser]) {
    if (req) {
      mod = _load(branch, parser)
    } else {
      try {
        mod = _load(branch, parser)
      } catch (_) {
        // istanbul ignore next
        mod = NULL
      }
    }
  } else {
    mod = _parsers[branch][parser]
  }

  return mod
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.parsers.css"></a>[module riot.parsers.css](#apidoc.module.riot.parsers.css)

#### <a name="apidoc.element.riot.parsers.css.less"></a>[function <span class="apidocSignatureSpan">riot.parsers.css.</span>less (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.less)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.css.sass"></a>[function <span class="apidocSignatureSpan">riot.parsers.css.</span>sass (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.sass)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.css.scss"></a>[function <span class="apidocSignatureSpan">riot.parsers.css.</span>scss (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.scss)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.css.stylus"></a>[function <span class="apidocSignatureSpan">riot.parsers.css.</span>stylus (p1, p2, p3, p4)](#apidoc.element.riot.parsers.css.stylus)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.parsers.html"></a>[module riot.parsers.html](#apidoc.module.riot.parsers.html)

#### <a name="apidoc.element.riot.parsers.html.jade"></a>[function <span class="apidocSignatureSpan">riot.parsers.html.</span>jade (p1, p2, p3, p4)](#apidoc.element.riot.parsers.html.jade)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.html.pug"></a>[function <span class="apidocSignatureSpan">riot.parsers.html.</span>pug (p1, p2, p3, p4)](#apidoc.element.riot.parsers.html.pug)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.parsers.js"></a>[module riot.parsers.js](#apidoc.module.riot.parsers.js)

#### <a name="apidoc.element.riot.parsers.js.buble"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>buble (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.buble)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.coffee"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>coffee (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.coffee)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.coffeescript"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>coffeescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.coffeescript)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.es6"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>es6 (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.es6)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.javascript"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>javascript (src)](#apidoc.element.riot.parsers.js.javascript)
- description and source-code
```javascript
function _none(src) {
  return src
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.livescript"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>livescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.livescript)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.none"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>none (src)](#apidoc.element.riot.parsers.js.none)
- description and source-code
```javascript
function _none(src) {
  return src
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.parsers.js.typescript"></a>[function <span class="apidocSignatureSpan">riot.parsers.js.</span>typescript (p1, p2, p3, p4)](#apidoc.element.riot.parsers.js.typescript)
- description and source-code
```javascript
function _loadParser(p1, p2, p3, p4) {
  var fn = _load(branch, parser)
  return fn(p1, p2, p3, p4)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.render"></a>[module riot.render](#apidoc.module.riot.render)

#### <a name="apidoc.element.riot.render.render"></a>[function <span class="apidocSignatureSpan">riot.</span>render (tagName, opts)](#apidoc.element.riot.render.render)
- description and source-code
```javascript
function render(tagName, opts) {
  var tag = render.tag(tagName, opts),
    html = getTagHtml(tag)
  // unmount the tag avoiding memory leaks
  tag.unmount()
  return html
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.render.dom"></a>[function <span class="apidocSignatureSpan">riot.render.</span>dom (tagName, opts)](#apidoc.element.riot.render.dom)
- description and source-code
```javascript
dom = function (tagName, opts) {
  return riot.render.tag(tagName, opts).root
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.render.tag"></a>[function <span class="apidocSignatureSpan">riot.render.</span>tag (tagName, opts)](#apidoc.element.riot.render.tag)
- description and source-code
```javascript
tag = function (tagName, opts) {
  var root = document.createElement(tagName),
    tag = riot.mount(root, opts)[0]
  return tag
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.riot_csp"></a>[module riot.riot_csp](#apidoc.module.riot.riot_csp)

#### <a name="apidoc.element.riot.riot_csp.Tag"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>Tag (el, opts)](#apidoc.element.riot.riot_csp.Tag)
- description and source-code
```javascript
function Tag$2(el, opts) {
  // get the tag properties from the class constructor
  var ref = this;
  var name = ref.name;
  var tmpl = ref.tmpl;
  var css = ref.css;
  var attrs = ref.attrs;
  var onCreate = ref.onCreate;
  // register a new tag and cache the class prototype
  if (!__TAG_IMPL[name]) {
    tag$1(name, tmpl, css, attrs, onCreate);
    // cache the class constructor
    __TAG_IMPL[name].class = this.constructor;
  }

  // mount the tag using the class instance
  mountTo(el, name, opts, this);
  // inject the component css
  if (css) { styleManager.inject(); }

  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.riot_csp.mixin"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>mixin (name, mix, g)](#apidoc.element.riot.riot_csp.mixin)
- description and source-code
```javascript
function mixin$1(name, mix, g) {
  // Unnamed global
  if (isObject(name)) {
    mixin$1(("__unnamed_" + (mixins_id++)), name, true);
    return
  }

  var store = g ? globals : mixins;

  // Getter
  if (!mix) {
    if (isUndefined(store[name]))
      { throw new Error('Unregistered mixin: ' + name) }

    return store[name]
  }

  // Setter
  store[name] = isFunction(mix) ?
    extend(mix.prototype, store[name] || {}) && mix :
    extend(store[name] || {}, mix);
}
```
- example usage
```shell
...

// add global mixins
var globalMixin = mixin$1(GLOBAL_MIXIN);

if (globalMixin && !skipAnonymous) {
  for (var i in globalMixin) {
    if (globalMixin.hasOwnProperty(i)) {
      this$1.mixin(globalMixin[i]);
    }
  }
}

if (impl.fn) { impl.fn.call(this, opts); }

if (!skipAnonymous) { this.trigger('before-mount'); }
...
```

#### <a name="apidoc.element.riot.riot_csp.mount"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>mount (selector, tagName, opts)](#apidoc.element.riot.riot_csp.mount)
- description and source-code
```javascript
function mount$1(selector, tagName, opts) {
  var tags = [];

  function pushTagsTo(root) {
    if (root.tagName) {
      var riotTag = getAttr(root, IS_DIRECTIVE);

      // have tagName? force riot-tag to be the same
      if (tagName && riotTag !== tagName) {
        riotTag = tagName;
        setAttr(root, IS_DIRECTIVE, tagName);
      }

      var tag = mountTo(root, riotTag || root.tagName.toLowerCase(), opts);

      if (tag)
        { tags.push(tag); }
    } else if (root.length)
      { each(root, pushTagsTo); } // assume nodeList
  }

  // inject styles into DOM
  styleManager.inject();

  if (isObject(tagName)) {
    opts = tagName;
    tagName = 0;
  }

  var elem;
  var allTags;

  // crawl the DOM to find the tag
  if (isString(selector)) {
    selector = selector === '*' ?
      // select all registered tags
      // & tags found with the riot-tag attribute set
      allTags = selectTags() :
      // or just the ones named like the selector
      selector + selectTags(selector.split(/, */));

    // make sure to pass always a selector
    // to the querySelectorAll function
    elem = selector ? $$(selector) : [];
  }
  else
    // probably you have passed already a tag or a NodeList
    { elem = selector; }

  // select all the registered and mount them inside their root elements
  if (tagName === '*') {
    // get all custom tags
    tagName = allTags || selectTags();
    // if the root els it's just a single tag
    if (elem.tagName)
      { elem = $$(tagName, elem); }
    else {
      // select all the children for all the different root elements
      var nodeList = [];

      each(elem, function (_el) { return nodeList.push($$(tagName, _el)); });

      elem = nodeList;
    }
    // get rid of the tagName
    tagName = 0;
  }

  pushTagsTo(elem);

  return tags
}
```
- example usage
```shell
...
'''

[Open this example on Plunker](http://riotjs.com/examples/plunker/?app=timer)

#### Mounting

''' javascript
riot.mount('timer', { start: 0 })
'''

#### Nesting

Custom tags lets you build complex views with HTML.

''' html
...
```

#### <a name="apidoc.element.riot.riot_csp.observable"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>observable (el)](#apidoc.element.riot.riot_csp.observable)
- description and source-code
```javascript
observable = function (el) {

<span class="apidocCodeCommentSpan">  /**
   * Extend the original object or create a new empty one
   * @type { Object }
   */
</span>
  el = el || {};

  /**
   * Private variables
   */
  var callbacks = {},
    slice = Array.prototype.slice;

  /**
   * Public Api
   */

  // extend the el object adding the observable methods
  Object.defineProperties(el, {
    /**
     * Listen to the given 'event' ands
     * execute the 'callback' each time an event is triggered.
     * @param  { String } event - event id
     * @param  { Function } fn - callback function
     * @returns { Object } el
     */
    on: {
      value: function(event, fn) {
        if (typeof fn == 'function')
          { (callbacks[event] = callbacks[event] || []).push(fn); }
        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Removes the given 'event' listeners
     * @param   { String } event - event id
     * @param   { Function } fn - callback function
     * @returns { Object } el
     */
    off: {
      value: function(event, fn) {
        if (event == '*' && !fn) { callbacks = {}; }
        else {
          if (fn) {
            var arr = callbacks[event];
            for (var i = 0, cb; cb = arr && arr[i]; ++i) {
              if (cb == fn) { arr.splice(i--, 1); }
            }
          } else { delete callbacks[event]; }
        }
        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Listen to the given 'event' and
     * execute the 'callback' at most once
     * @param   { String } event - event id
     * @param   { Function } fn - callback function
     * @returns { Object } el
     */
    one: {
      value: function(event, fn) {
        function on() {
          el.off(event, on);
          fn.apply(el, arguments);
        }
        return el.on(event, on)
      },
      enumerable: false,
      writable: false,
      configurable: false
    },

    /**
     * Execute all callback functions that listen to
     * the given 'event'
     * @param   { String } event - event id
     * @returns { Object } el
     */
    trigger: {
      value: function(event) {
        var arguments$1 = arguments;


        // getting the arguments
        var arglen = arguments.length - 1,
          args = new Array(arglen),
          fns,
          fn,
          i;

        for (i = 0; i < arglen; i++) {
          args[i] = arguments$1[i + 1]; // skip first argument
        }

        fns = slice.call(callbacks[event] || [], 0);

        for (i = 0; fn = fns[i]; ++i) {
          fn.apply(el, args);
        }

        if (callbacks['*'] && event != '*')
          { el.trigger.apply(el, ['*', event].concat(args)); }

        return el
      },
      enumerable: false,
      writable: false,
      configurable: false
    }
  });

  return el

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.riot_csp.tag"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>tag (name, tmpl, css, attrs, fn)](#apidoc.element.riot.riot_csp.tag)
- description and source-code
```javascript
function tag$1(name, tmpl, css, attrs, fn) {
  if (isFunction(attrs)) {
    fn = attrs;

    if (/^[\w\-]+\s?=/.test(css)) {
      attrs = css;
      css = '';
    } else
      { attrs = ''; }
  }

  if (css) {
    if (isFunction(css))
      { fn = css; }
    else
      { styleManager.add(css); }
  }

  name = name.toLowerCase();
  __TAG_IMPL[name] = { name: name, tmpl: tmpl, attrs: attrs, fn: fn };

  return name
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.riot_csp.tag2"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>tag2 (name, tmpl, css, attrs, fn)](#apidoc.element.riot.riot_csp.tag2)
- description and source-code
```javascript
function tag2$1(name, tmpl, css, attrs, fn) {
  if (css) { styleManager.add(css, name); }

  __TAG_IMPL[name] = { name: name, tmpl: tmpl, attrs: attrs, fn: fn };

  return name
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.riot_csp.unregister"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>unregister (name)](#apidoc.element.riot.riot_csp.unregister)
- description and source-code
```javascript
function unregister$1(name) {
  delete __TAG_IMPL[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.riot_csp.update"></a>[function <span class="apidocSignatureSpan">riot.riot_csp.</span>update ()](#apidoc.element.riot.riot_csp.update)
- description and source-code
```javascript
function update$1() {
  return each(__TAGS_CACHE, function (tag) { return tag.update(); })
}
```
- example usage
```shell
...
<timer>

<p>Seconds Elapsed: { time }</p>

this.time = opts.start || 0

tick() {
  this.update({ time: ++this.time })
}

var timer = setInterval(this.tick, 1000)

this.on('unmount', function() {
  clearInterval(timer)
})
...
```



# <a name="apidoc.module.riot.util"></a>[module riot.util](#apidoc.module.riot.util)

#### <a name="apidoc.element.riot.util.brackets"></a>[function <span class="apidocSignatureSpan">riot.util.</span>brackets (reOrIdx)](#apidoc.element.riot.util.brackets)
- description and source-code
```javascript
function _brackets(reOrIdx) {
  return reOrIdx instanceof RegExp ? _regex(reOrIdx) : _cache[reOrIdx]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tmpl"></a>[function <span class="apidocSignatureSpan">riot.util.</span>tmpl (str, data)](#apidoc.element.riot.util.tmpl)
- description and source-code
```javascript
function _tmpl(str, data) {
  if (!str) { return str }

  return (_cache[str] || (_cache[str] = _create(str))).call(data, _logErr)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.util.brackets"></a>[module riot.util.brackets](#apidoc.module.riot.util.brackets)

#### <a name="apidoc.element.riot.util.brackets.brackets"></a>[function <span class="apidocSignatureSpan">riot.util.</span>brackets (reOrIdx)](#apidoc.element.riot.util.brackets.brackets)
- description and source-code
```javascript
function _brackets(reOrIdx) {
  return reOrIdx instanceof RegExp ? _regex(reOrIdx) : _cache[reOrIdx]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.brackets.array"></a>[function <span class="apidocSignatureSpan">riot.util.brackets.</span>array (pair)](#apidoc.element.riot.util.brackets.array)
- description and source-code
```javascript
function array(pair) {
  return pair ? _create(pair) : _cache
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.brackets.hasExpr"></a>[function <span class="apidocSignatureSpan">riot.util.brackets.</span>hasExpr (str)](#apidoc.element.riot.util.brackets.hasExpr)
- description and source-code
```javascript
function hasExpr(str) {
  return _cache[4].test(str)
}
```
- example usage
```shell
...

var RefExpr = {
init: function init(dom, parent, attrName, attrValue) {
  this.dom = dom;
  this.attr = attrName;
  this.rawValue = attrValue;
  this.parent = parent;
  this.hasExp = csp_tmpl_1.hasExpr(attrValue);
  return this
},
update: function update() {
  var old = this.value;
  var customParent = this.parent && getImmediateCustomParentTag(this.parent);
  // if the referenced element is a custom tag, then we set the tag itself, rather than DOM
  var tagOrDom = this.tag || this.dom;
...
```

#### <a name="apidoc.element.riot.util.brackets.loopKeys"></a>[function <span class="apidocSignatureSpan">riot.util.brackets.</span>loopKeys (expr)](#apidoc.element.riot.util.brackets.loopKeys)
- description and source-code
```javascript
function loopKeys(expr) {
  var m = expr.match(_cache[9]);

  return m
    ? { key: m[1], pos: m[2], val: _cache[0] + m[3].trim() + _cache[1] }
    : { val: expr.trim() }
}
```
- example usage
```shell
...
  oldItems = [],
  hasKeys,
  isLoop = true,
  isAnonymous = !__TAG_IMPL[tagName],
  isVirtual = dom.tagName === 'VIRTUAL';

// parse the each expression
expr = csp_tmpl_1.loopKeys(expr);
expr.isLoop = true;

if (ifExpr) { remAttr(dom, CONDITIONAL_DIRECTIVE); }

// insert a marked where the loop tags will be injected
parentNode.insertBefore(placeholder, dom);
parentNode.removeChild(dom);
...
```

#### <a name="apidoc.element.riot.util.brackets.set"></a>[function <span class="apidocSignatureSpan">riot.util.brackets.</span>set (pair)](#apidoc.element.riot.util.brackets.set)
- description and source-code
```javascript
function _reset(pair) {
  if ((pair || (pair = DEFAULT)) !== _cache[8]) {
    _cache = _create(pair);
    _regex = pair === DEFAULT ? _loopback : _rewrite;
    _cache[9] = _regex(_pairs[9]);
  }
  cachedBrackets = pair;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.brackets.split"></a>[function <span class="apidocSignatureSpan">riot.util.brackets.</span>split (str, tmpl, _bp)](#apidoc.element.riot.util.brackets.split)
- description and source-code
```javascript
function split(str, tmpl, _bp) {
  // istanbul ignore next: _bp is for the compiler
  if (!_bp) { _bp = _cache; }

  var
    parts = [],
    match,
    isexpr,
    start,
    pos,
    re = _bp[6];

  isexpr = start = re.lastIndex = 0;

  while ((match = re.exec(str))) {

    pos = match.index;

    if (isexpr) {

      if (match[2]) {
        re.lastIndex = skipBraces(str, match[2], re.lastIndex);
        continue
      }
      if (!match[3]) {
        continue
      }
    }

    if (!match[1]) {
      unescapeStr(str.slice(start, pos));
      start = re.lastIndex;
      re = _bp[6 + (isexpr ^= 1)];
      re.lastIndex = start;
    }
  }

  if (str && start < str.length) {
    unescapeStr(str.slice(start));
  }

  return parts

  function unescapeStr (s) {
    if (tmpl || isexpr) {
      parts.push(s && s.replace(_bp[5], '$1'));
    } else {
      parts.push(s);
    }
  }

  function skipBraces (s, ch, ix) {
    var
      match,
      recch = FINDBRACES[ch];

    recch.lastIndex = ix;
    ix = 1;
    while ((match = recch.exec(s))) {
      if (match[1] &&
        !(match[1] === ch ? ++ix : --ix)) { break }
    }
    return ix ? s.length : recch.lastIndex
  }
}
```
- example usage
```shell
...
  re.source.replace(/{/g, bp[2]).replace(/}/g, bp[3]), re.global ? REGLOB : ''
)
  }

  function _create (pair) {
if (pair === DEFAULT) { return _pairs }

var arr = pair.split(' ');

if (arr.length !== 2 || UNSUPPORTED.test(pair)) {
  throw new Error('Unsupported brackets "' + pair + '"')
}
arr = arr.concat(pair.replace(NEED_ESCAPE, '\\').split(' '));

arr[4] = _rewrite(arr[1].length > 1 ? /{[\S\s]*?}/ : _pairs[4], arr);
...
```



# <a name="apidoc.module.riot.util.check"></a>[module riot.util.check](#apidoc.module.riot.util.check)

#### <a name="apidoc.element.riot.util.check.isArray"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isArray (value)](#apidoc.element.riot.util.check.isArray)
- description and source-code
```javascript
function isArray(value) {
  return Array.isArray(value) || value instanceof Array
}
```
- example usage
```shell
...

/**
* Check if passed argument is a kind of array
* @param   { * } value -
* @returns { Boolean } -
*/
function isArray(value) {
 return Array.isArray(value) || value instanceof Array
}

/**
* Check whether object's property could be overridden
* @param   { Object }  obj - source object
* @param   { String }  key - object property
* @returns { Boolean } -
...
```

#### <a name="apidoc.element.riot.util.check.isBlank"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isBlank (value)](#apidoc.element.riot.util.check.isBlank)
- description and source-code
```javascript
function isBlank(value) {
  return isUndefined(value) || value === null || value === ''
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isBoolAttr"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isBoolAttr (value)](#apidoc.element.riot.util.check.isBoolAttr)
- description and source-code
```javascript
function isBoolAttr(value) {
  return RE_BOOL_ATTRS.test(value)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isFunction"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isFunction (value)](#apidoc.element.riot.util.check.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  return typeof value === T_FUNCTION
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isObject"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isObject (value)](#apidoc.element.riot.util.check.isObject)
- description and source-code
```javascript
function isObject(value) {
  return value && typeof value === T_OBJECT // typeof null is 'object'
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isReservedName"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isReservedName (value)](#apidoc.element.riot.util.check.isReservedName)
- description and source-code
```javascript
function isReservedName(value) {
  return RE_RESERVED_NAMES.test(value)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isString"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isString (value)](#apidoc.element.riot.util.check.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value === T_STRING
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isUndefined"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isUndefined (value)](#apidoc.element.riot.util.check.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return typeof value === T_UNDEF
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.check.isWritable"></a>[function <span class="apidocSignatureSpan">riot.util.check.</span>isWritable (obj, key)](#apidoc.element.riot.util.check.isWritable)
- description and source-code
```javascript
function isWritable(obj, key) {
  var descriptor = Object.getOwnPropertyDescriptor(obj, key);
  return isUndefined(obj[key]) || descriptor && descriptor.writable
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.util.dom"></a>[module riot.util.dom](#apidoc.module.riot.util.dom)

#### <a name="apidoc.element.riot.util.dom.createDOMPlaceholder"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>createDOMPlaceholder ()](#apidoc.element.riot.util.dom.createDOMPlaceholder)
- description and source-code
```javascript
function createDOMPlaceholder() {
  return document.createTextNode('')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.createFrag"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>createFrag ()](#apidoc.element.riot.util.dom.createFrag)
- description and source-code
```javascript
function createFrag() {
  return document.createDocumentFragment()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.getAttr"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>getAttr (dom, name)](#apidoc.element.riot.util.dom.getAttr)
- description and source-code
```javascript
function getAttr(dom, name) {
  return dom.getAttribute(name)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.mkEl"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>mkEl (name)](#apidoc.element.riot.util.dom.mkEl)
- description and source-code
```javascript
function mkEl(name) {
  return document.createElement(name)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.remAttr"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>remAttr (dom, name)](#apidoc.element.riot.util.dom.remAttr)
- description and source-code
```javascript
function remAttr(dom, name) {
  dom.removeAttribute(name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.safeInsert"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>safeInsert (root, curr, next)](#apidoc.element.riot.util.dom.safeInsert)
- description and source-code
```javascript
function safeInsert(root, curr, next) {
  root.insertBefore(curr, next.parentNode && next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.setAttr"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>setAttr (dom, name, val)](#apidoc.element.riot.util.dom.setAttr)
- description and source-code
```javascript
function setAttr(dom, name, val) {
  var xlink = XLINK_REGEX.exec(name);
  if (xlink && xlink[1])
    { dom.setAttributeNS(XLINK_NS, xlink[1], val); }
  else
    { dom.setAttribute(name, val); }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.setInnerHTML"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>setInnerHTML (container, html)](#apidoc.element.riot.util.dom.setInnerHTML)
- description and source-code
```javascript
function setInnerHTML(container, html) {
  if (!isUndefined(container.innerHTML))
    { container.innerHTML = html; }
    // some browsers do not support innerHTML on the SVGs tags
  else {
    var doc = new DOMParser().parseFromString(html, 'application/xml');
    var node = container.ownerDocument.importNode(doc.documentElement, true);
    container.appendChild(node);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.styleObjectToString"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>styleObjectToString (style)](#apidoc.element.riot.util.dom.styleObjectToString)
- description and source-code
```javascript
function styleObjectToString(style) {
  return Object.keys(style).reduce(function (acc, prop) {
    return (acc + " " + prop + ": " + (style[prop]) + ";")
  }, '')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.toggleVisibility"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>toggleVisibility (dom, show)](#apidoc.element.riot.util.dom.toggleVisibility)
- description and source-code
```javascript
function toggleVisibility(dom, show) {
  dom.style.display = show ? '' : 'none';
  dom['hidden'] = show ? false : true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.walkAttrs"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>walkAttrs (html, fn)](#apidoc.element.riot.util.dom.walkAttrs)
- description and source-code
```javascript
function walkAttrs(html, fn) {
  if (!html)
    { return }
  var m;
  while (m = RE_HTML_ATTRS.exec(html))
    { fn(m[1].toLowerCase(), m[2] || m[3] || m[4]); }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.dom.walkNodes"></a>[function <span class="apidocSignatureSpan">riot.util.dom.</span>walkNodes (dom, fn, context)](#apidoc.element.riot.util.dom.walkNodes)
- description and source-code
```javascript
function walkNodes(dom, fn, context) {
  if (dom) {
    var res = fn(dom, context);
    var next;
    // stop the recursion
    if (res === false) { return }

    dom = dom.firstChild;

    while (dom) {
      next = dom.nextSibling;
      walkNodes(dom, fn, res);
      dom = next;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.util.misc"></a>[module riot.util.misc](#apidoc.module.riot.util.misc)

#### <a name="apidoc.element.riot.util.misc.contains"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>contains (array, item)](#apidoc.element.riot.util.misc.contains)
- description and source-code
```javascript
function contains(array, item) {
  return array.indexOf(item) !== -1
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.misc.defineProperty"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>defineProperty (el, key, value, options)](#apidoc.element.riot.util.misc.defineProperty)
- description and source-code
```javascript
function defineProperty(el, key, value, options) {
  Object.defineProperty(el, key, extend({
    value: value,
    enumerable: false,
    writable: false,
    configurable: true
  }, options));
  return el
}
```
- example usage
```shell
...
    var error = new Error(msg);
    try {
        throw error;
    } catch (base) {
        /* istanbul ignore else */
        if (Object.create && Object.defineProperty) {
            error = Object.create(base);
            Object.defineProperty(error, 'column', { value: column });
        }
    } finally {
        return error;
    }
}

function createError(line, pos, description) {
...
```

#### <a name="apidoc.element.riot.util.misc.each"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>each (list, fn)](#apidoc.element.riot.util.misc.each)
- description and source-code
```javascript
function each(list, fn) {
  var len = list ? list.length : 0;
  var i = 0;
  for (; i < len; ++i) {
    fn(list[i], i);
  }
  return list
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.misc.extend"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>extend (src)](#apidoc.element.riot.util.misc.extend)
- description and source-code
```javascript
function extend(src) {
  var obj, args = arguments;
  for (var i = 1; i < args.length; ++i) {
    if (obj = args[i]) {
      for (var key in obj) {
        // check if this property of the source object could be overridden
        if (isWritable(src, key))
          { src[key] = obj[key]; }
      }
    }
  }
  return src
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.misc.startsWith"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>startsWith (str, value)](#apidoc.element.riot.util.misc.startsWith)
- description and source-code
```javascript
function startsWith(str, value) {
  return str.slice(0, value.length) === value
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.misc.toCamel"></a>[function <span class="apidocSignatureSpan">riot.util.misc.</span>toCamel (str)](#apidoc.element.riot.util.misc.toCamel)
- description and source-code
```javascript
function toCamel(str) {
  return str.replace(/-(\w)/g, function (_, c) { return c.toUpperCase(); })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.util.styleManager"></a>[module riot.util.styleManager](#apidoc.module.riot.util.styleManager)

#### <a name="apidoc.element.riot.util.styleManager.add"></a>[function <span class="apidocSignatureSpan">riot.util.styleManager.</span>add (css, name)](#apidoc.element.riot.util.styleManager.add)
- description and source-code
```javascript
function add(css, name) {
  if (name) { byName[name] = css; }
  else { remainder.push(css); }
  needsInject = true;
}
```
- example usage
```shell
...
      { attrs = ''; }
  }

  if (css) {
    if (isFunction(css))
      { fn = css; }
    else
      { styleManager.add(css); }
  }

  name = name.toLowerCase();
  __TAG_IMPL[name] = { name: name, tmpl: tmpl, attrs: attrs, fn: fn };

  return name
}
...
```

#### <a name="apidoc.element.riot.util.styleManager.inject"></a>[function <span class="apidocSignatureSpan">riot.util.styleManager.</span>inject ()](#apidoc.element.riot.util.styleManager.inject)
- description and source-code
```javascript
function inject() {
  if (!WIN || !needsInject) { return }
  needsInject = false;
  var style = Object.keys(byName)
    .map(function(k) { return byName[k] })
    .concat(remainder).join('\n');
<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (cssTextProp) { cssTextProp.cssText = style; }
  else { styleNode.innerHTML = style; }
}
```
- example usage
```shell
...
   // cache the class constructor
   __TAG_IMPL[name].class = this.constructor;
 }

 // mount the tag using the class instance
 mountTo(el, name, opts, this);
 // inject the component css
 if (css) { styleManager.inject(); }

 return this
}

/**
* Create a new riot tag implementation
* @param   { String }   name - name/id of the new riot tag
...
```



# <a name="apidoc.module.riot.util.tags"></a>[module riot.util.tags](#apidoc.module.riot.util.tags)

#### <a name="apidoc.element.riot.util.tags.arrayishAdd"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>arrayishAdd (obj, key, value, ensureArray, index)](#apidoc.element.riot.util.tags.arrayishAdd)
- description and source-code
```javascript
function arrayishAdd(obj, key, value, ensureArray, index) {
  var dest = obj[key];
  var isArr = isArray(dest);
  var hasIndex = !isUndefined(index);

  if (dest && dest === value) { return }

  // if the key was never set, set it once
  if (!dest && ensureArray) { obj[key] = [value]; }
  else if (!dest) { obj[key] = value; }
  // if it was an array and not yet set
  else {
    if (isArr) {
      var oldIndex = dest.indexOf(value);
      // this item never changed its position
      if (oldIndex === index) { return }
      // remove the item from its old position
      if (oldIndex !== -1) { dest.splice(oldIndex, 1); }
      // move or add the item
      if (hasIndex) {
        dest.splice(index, 0, value);
      } else {
        dest.push(value);
      }
    } else { obj[key] = [dest, value]; }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.arrayishRemove"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>arrayishRemove (obj, key, value, ensureArray)](#apidoc.element.riot.util.tags.arrayishRemove)
- description and source-code
```javascript
function arrayishRemove(obj, key, value, ensureArray) {
  if (isArray(obj[key])) {
    var index = obj[key].indexOf(value);
    if (index !== -1) { obj[key].splice(index, 1); }
    if (!obj[key].length) { delete obj[key]; }
    else if (obj[key].length === 1 && !ensureArray) { obj[key] = obj[key][0]; }
  } else
    { delete obj[key]; } // otherwise just delete the key
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.cleanUpData"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>cleanUpData (data)](#apidoc.element.riot.util.tags.cleanUpData)
- description and source-code
```javascript
function cleanUpData(data) {
  if (!(data instanceof Tag$1) && !(data && isFunction(data.trigger)))
    { return data }

  var o = {};
  for (var key in data) {
    if (!RE_RESERVED_NAMES.test(key)) { o[key] = data[key]; }
  }
  return o
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.getImmediateCustomParentTag"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>getImmediateCustomParentTag (tag)](#apidoc.element.riot.util.tags.getImmediateCustomParentTag)
- description and source-code
```javascript
function getImmediateCustomParentTag(tag) {
  var ptag = tag;
  while (ptag.__.isAnonymous) {
    if (!ptag.parent) { break }
    ptag = ptag.parent;
  }
  return ptag
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.getTag"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>getTag (dom)](#apidoc.element.riot.util.tags.getTag)
- description and source-code
```javascript
function getTag(dom) {
  return dom.tagName && __TAG_IMPL[getAttr(dom, IS_DIRECTIVE) ||
    getAttr(dom, IS_DIRECTIVE) || dom.tagName.toLowerCase()]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.getTagName"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>getTagName (dom, skipDataIs)](#apidoc.element.riot.util.tags.getTagName)
- description and source-code
```javascript
function getTagName(dom, skipDataIs) {
  var child = getTag(dom),
    namedTag = !skipDataIs && getAttr(dom, IS_DIRECTIVE);
  return namedTag && !tmpl.hasExpr(namedTag) ?
                namedTag :
              child ? child.name : dom.tagName.toLowerCase()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.inheritFrom"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>inheritFrom (target, propsInSyncWithParent)](#apidoc.element.riot.util.tags.inheritFrom)
- description and source-code
```javascript
function inheritFrom(target, propsInSyncWithParent) {
  var this$1 = this;

  each(Object.keys(target), function (k) {
    // some properties must be always in sync with the parent tag
    var mustSync = !isReservedName(k) && contains(propsInSyncWithParent, k);

    if (isUndefined(this$1[k]) || mustSync) {
      // track the property to keep in sync
      // so we can keep it updated
      if (!mustSync) { propsInSyncWithParent.push(k); }
      this$1[k] = target[k];
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.initChildTag"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>initChildTag (child, opts, innerHTML, parent)](#apidoc.element.riot.util.tags.initChildTag)
- description and source-code
```javascript
function initChildTag(child, opts, innerHTML, parent) {
  var tag = new Tag$1(child, opts, innerHTML),
    tagName = opts.tagName || getTagName(opts.root, true),
    ptag = getImmediateCustomParentTag(parent);
  // fix for the parent attribute in the looped elements
  defineProperty(tag, 'parent', ptag);
  // store the real parent tag
  // in some cases this could be different from the custom parent tag
  // for example in nested loops
  tag.__.parent = parent;

  // add this tag to the custom parent tag
  arrayishAdd(ptag.tags, tagName, tag);

  // and also to the real parent tag
  if (ptag !== parent)
    { arrayishAdd(parent.tags, tagName, tag); }

  // empty the child node once we got its template
  // to avoid that its children get compiled multiple times
  opts.root.innerHTML = '';

  return tag
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.makeReplaceVirtual"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>makeReplaceVirtual (tag, ref)](#apidoc.element.riot.util.tags.makeReplaceVirtual)
- description and source-code
```javascript
function makeReplaceVirtual(tag, ref) {
  var frag = createFrag();
  makeVirtual.call(tag, frag);
  ref.parentNode.replaceChild(frag, ref);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.makeVirtual"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>makeVirtual (src, target)](#apidoc.element.riot.util.tags.makeVirtual)
- description and source-code
```javascript
function makeVirtual(src, target) {
  var this$1 = this;

  var head = createDOMPlaceholder(),
    tail = createDOMPlaceholder(),
    frag = createFrag(),
    sib, el;

  this.root.insertBefore(head, this.root.firstChild);
  this.root.appendChild(tail);

  this.__.head = el = head;
  this.__.tail = tail;

  while (el) {
    sib = el.nextSibling;
    frag.appendChild(el);
    this$1.__.virts.push(el); // hold for unmounting
    el = sib;
  }

  if (target)
    { src.insertBefore(frag, target.__.head); }
  else
    { src.appendChild(frag); }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.mountTo"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>mountTo (root, tagName, opts, ctx)](#apidoc.element.riot.util.tags.mountTo)
- description and source-code
```javascript
function mountTo(root, tagName, opts, ctx) {
  var impl = __TAG_IMPL[tagName],
    implClass = __TAG_IMPL[tagName].class,
    tag = ctx || (implClass ? Object.create(implClass.prototype) : {}),
    // cache the inner HTML to fix #855
    innerHTML = root._innerHTML = root._innerHTML || root.innerHTML;

  // clear the inner html
  root.innerHTML = '';

  var conf = extend({ root: root, opts: opts }, { parent: opts ? opts.parent : null });

  if (impl && root) { Tag$1.apply(tag, [impl, conf, innerHTML]); }

  if (tag && tag.mount) {
    tag.mount(true);
    // add this tag to the virtualDom variable
    if (!contains(__TAGS_CACHE, tag)) { __TAGS_CACHE.push(tag); }
  }

  return tag
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.moveChildTag"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>moveChildTag (tagName, newPos)](#apidoc.element.riot.util.tags.moveChildTag)
- description and source-code
```javascript
function moveChildTag(tagName, newPos) {
  var parent = this.parent,
    tags;
  // no parent no move
  if (!parent) { return }

  tags = parent.tags[tagName];

  if (isArray(tags))
    { tags.splice(newPos, 0, tags.splice(tags.indexOf(this), 1)[0]); }
  else { arrayishAdd(parent.tags, tagName, this); }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.moveVirtual"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>moveVirtual (src, target)](#apidoc.element.riot.util.tags.moveVirtual)
- description and source-code
```javascript
function moveVirtual(src, target) {
  var this$1 = this;

  var el = this.__.head,
    frag = createFrag(),
    sib;

  while (el) {
    sib = el.nextSibling;
    frag.appendChild(el);
    el = sib;
    if (el === this$1.__.tail) {
      frag.appendChild(el);
      src.insertBefore(frag, target.__.head);
      break
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.selectTags"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>selectTags (tags)](#apidoc.element.riot.util.tags.selectTags)
- description and source-code
```javascript
function selectTags(tags) {
  // select all tags
  if (!tags) {
    var keys = Object.keys(__TAG_IMPL);
    return keys + selectTags(keys)
  }

  return tags
    .filter(function (t) { return !/[^-\w]/.test(t); })
    .reduce(function (list, t) {
      var name = t.trim().toLowerCase();
      return list + ",[" + IS_DIRECTIVE + "=\"" + name + "\"]"
    }, '')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tags.unmountAll"></a>[function <span class="apidocSignatureSpan">riot.util.tags.</span>unmountAll (expressions)](#apidoc.element.riot.util.tags.unmountAll)
- description and source-code
```javascript
function unmountAll(expressions) {
  each(expressions, function(expr) {
    if (expr instanceof Tag$1) { expr.unmount(true); }
    else if (expr.unmount) { expr.unmount(); }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.riot.util.tmpl"></a>[module riot.util.tmpl](#apidoc.module.riot.util.tmpl)

#### <a name="apidoc.element.riot.util.tmpl.tmpl"></a>[function <span class="apidocSignatureSpan">riot.util.</span>tmpl (str, data)](#apidoc.element.riot.util.tmpl.tmpl)
- description and source-code
```javascript
function _tmpl(str, data) {
  if (!str) { return str }

  return (_cache[str] || (_cache[str] = _create(str))).call(data, _logErr)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tmpl.clearCache"></a>[function <span class="apidocSignatureSpan">riot.util.tmpl.</span>clearCache ()](#apidoc.element.riot.util.tmpl.clearCache)
- description and source-code
```javascript
clearCache = function () { _cache = {}; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.riot.util.tmpl.hasExpr"></a>[function <span class="apidocSignatureSpan">riot.util.tmpl.</span>hasExpr (str)](#apidoc.element.riot.util.tmpl.hasExpr)
- description and source-code
```javascript
function hasExpr(str) {
  return _cache[4].test(str)
}
```
- example usage
```shell
...

var RefExpr = {
init: function init(dom, parent, attrName, attrValue) {
  this.dom = dom;
  this.attr = attrName;
  this.rawValue = attrValue;
  this.parent = parent;
  this.hasExp = csp_tmpl_1.hasExpr(attrValue);
  return this
},
update: function update() {
  var old = this.value;
  var customParent = this.parent && getImmediateCustomParentTag(this.parent);
  // if the referenced element is a custom tag, then we set the tag itself, rather than DOM
  var tagOrDom = this.tag || this.dom;
...
```

#### <a name="apidoc.element.riot.util.tmpl.loopKeys"></a>[function <span class="apidocSignatureSpan">riot.util.tmpl.</span>loopKeys (expr)](#apidoc.element.riot.util.tmpl.loopKeys)
- description and source-code
```javascript
function loopKeys(expr) {
  var m = expr.match(_cache[9]);

  return m
    ? { key: m[1], pos: m[2], val: _cache[0] + m[3].trim() + _cache[1] }
    : { val: expr.trim() }
}
```
- example usage
```shell
...
  oldItems = [],
  hasKeys,
  isLoop = true,
  isAnonymous = !__TAG_IMPL[tagName],
  isVirtual = dom.tagName === 'VIRTUAL';

// parse the each expression
expr = csp_tmpl_1.loopKeys(expr);
expr.isLoop = true;

if (ifExpr) { remAttr(dom, CONDITIONAL_DIRECTIVE); }

// insert a marked where the loop tags will be injected
parentNode.insertBefore(placeholder, dom);
parentNode.removeChild(dom);
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
