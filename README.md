# api documentation for  [nan (v2.5.1)](https://github.com/nodejs/nan#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nan.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nan) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nan.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nan)
#### Native Abstractions for Node.js: C++ header for Node 0.8 -> 7 compatibility

[![NPM](https://nodei.co/npm/nan.png?downloads=true)](https://www.npmjs.com/package/nan)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nan/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nan_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nan/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-nan/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/nodejs/nan/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "Benjamin Byholm",
            "email": "bbyholm@abo.fi",
            "url": "https://github.com/kkoopa/"
        },
        {
            "name": "Trevor Norris",
            "email": "trev.norris@gmail.com",
            "url": "https://github.com/trevnorris"
        },
        {
            "name": "Nathan Rajlich",
            "email": "nathan@tootallnate.net",
            "url": "https://github.com/TooTallNate"
        },
        {
            "name": "Brett Lawson",
            "email": "brett19@gmail.com",
            "url": "https://github.com/brett19"
        },
        {
            "name": "Ben Noordhuis",
            "email": "info@bnoordhuis.nl",
            "url": "https://github.com/bnoordhuis"
        },
        {
            "name": "David Siegel",
            "email": "david@artcom.de",
            "url": "https://github.com/agnat"
        }
    ],
    "dependencies": {},
    "description": "Native Abstractions for Node.js: C++ header for Node 0.8 -> 7 compatibility",
    "devDependencies": {
        "bindings": "~1.2.1",
        "commander": "^2.8.1",
        "glob": "^5.0.14",
        "node-gyp": "~3.0.1",
        "readable-stream": "^2.1.4",
        "tap": "~0.7.1",
        "xtend": "~4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d5b01691253326a97a2bbee9e61c55d8d60351e2",
        "tarball": "https://registry.npmjs.org/nan/-/nan-2.5.1.tgz"
    },
    "homepage": "https://github.com/nodejs/nan#readme",
    "license": "MIT",
    "main": "include_dirs.js",
    "maintainers": [
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "kkoopa",
            "email": "bbyholm@abo.fi"
        }
    ],
    "name": "nan",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nodejs/nan.git"
    },
    "scripts": {
        "docs": "doc/.build.sh",
        "rebuild-tests": "node-gyp rebuild --msvs_version=2013 --directory test",
        "test": "tap --gc --stderr test/js/*-test.js"
    },
    "version": "2.5.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nan](#apidoc.module.nan)



# <a name="apidoc.module.nan"></a>[module nan](#apidoc.module.nan)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
