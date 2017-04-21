# npmdoc-write

#### api documentation for  [write (v0.3.3)](https://github.com/jonschlinkert/write)  [![npm package](https://img.shields.io/npm/v/npmdoc-write.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-write) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-write.svg)](https://travis-ci.org/npmdoc/node-npmdoc-write)

#### Write files to disk, creating intermediate directories if they don't exist.

[![NPM](https://nodei.co/npm/write.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/write)

- [https://npmdoc.github.io/node-npmdoc-write/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-write/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-write/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-write/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-write/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-write/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "write",
    "description": "Write files to disk, creating intermediate directories if they don't exist.",
    "version": "0.3.3",
    "homepage": "https://github.com/jonschlinkert/write",
    "author": "Jon Schlinkert (https://github.com/jonschlinkert)",
    "contributors": [
        "Charlike Mike Reagent (https://i.am.charlike.online)",
        "Jon Schlinkert <jon.schlinkert@sellside.com> (http://twitter.com/jonschlinkert)"
    ],
    "repository": "jonschlinkert/write",
    "bugs": {
        "url": "https://github.com/jonschlinkert/write/issues"
    },
    "license": "MIT",
    "files": [
        "index.js"
    ],
    "main": "index.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "dependencies": {
        "fs-exists-sync": "^0.1.0",
        "mkdirp": "^0.5.1"
    },
    "devDependencies": {
        "async": "^2.1.5",
        "delete": "^0.3.2",
        "gulp-format-md": "^0.1.11",
        "mocha": "^3.2.0"
    },
    "keywords": [
        "file",
        "filepath",
        "files",
        "filesystem",
        "folder",
        "fs",
        "fs.writeFile",
        "fs.writeFileSync",
        "path",
        "write"
    ],
    "verb": {
        "run": true,
        "toc": false,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "related": {
            "list": [
                "delete",
                "read-data",
                "read-json",
                "read-yaml",
                "write-json",
                "write-yaml"
            ]
        },
        "reflinks": [
            "verb"
        ],
        "lint": {
            "reflinks": true
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
