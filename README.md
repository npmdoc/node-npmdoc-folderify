# npmdoc-folderify

#### api documentation for  [folderify (v1.2.1)](https://github.com/parro-it/folderify)  [![npm package](https://img.shields.io/npm/v/npmdoc-folderify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-folderify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-folderify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-folderify)

#### Expose the content of each file in a folder as an object property.

[![NPM](https://nodei.co/npm/folderify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/folderify)

- [https://npmdoc.github.io/node-npmdoc-folderify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-folderify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-folderify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-folderify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-folderify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-folderify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "folderify",
    "description": "Expose the content of each file in a folder as an object property.",
    "version": "1.2.1",
    "homepage": "https://github.com/parro-it/folderify",
    "license": "MIT",
    "author": {
        "name": "Andrea Parodi"
    },
    "eslintConfig": {
        "extends": "eslint-config-semistandard"
    },
    "repository": "parro-it/folderify.git",
    "licenses": "MIT",
    "main": "lib/folderify",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "eslint lib test/folderify_test.js && node test/folderify_test.js | faucet"
    },
    "devDependencies": {
        "browserify": "^11.0.0",
        "eslint": "^1.10.3",
        "eslint-plugin-standard": "^1.3.1",
        "eslint-config-semistandard": "^5.0.0",
        "eslint-config-standard": "^4.4.0",
        "expect.js": "^0.3.1",
        "faucet": "0.0.1",
        "tape": "^4.4.0"
    },
    "keywords": [
        "folder",
        "content",
        "file",
        "require",
        "readFileSync",
        "browserify",
        "browserify-plugin",
        "browserify-transform"
    ],
    "dependencies": {
        "brfs": "~1.0.2",
        "concat-stream": "^1.5.0",
        "falafel": "^1.2.0",
        "include-folder": "^1.0.0",
        "through": "^2.3.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
