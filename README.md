# npmdoc-qrcode-reader

#### basic api documentation for  [qrcode-reader (v0.2.2)](https://github.com/edi9999/jsqrcode)  [![npm package](https://img.shields.io/npm/v/npmdoc-qrcode-reader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-qrcode-reader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-qrcode-reader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-qrcode-reader)

#### fork of lazarsoft's jsqrcode for node

[![NPM](https://nodei.co/npm/qrcode-reader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qrcode-reader)

- [https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-qrcode-reader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/edi9999/jsqrcode/issues"
    },
    "dependencies": {},
    "description": "fork of lazarsoft's jsqrcode for node",
    "devDependencies": {
        "chai": "^1.9.1",
        "eslint": "^2.13.1",
        "mocha": "^2.4.5",
        "png-js": "^0.1.1",
        "rollup": "^0.34.13",
        "uglify-js": "^2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1f202f2461d0eeed85e8794a6f44fe418dda7f87",
        "tarball": "https://registry.npmjs.org/qrcode-reader/-/qrcode-reader-0.2.2.tgz"
    },
    "gitHead": "c72886b18197be2dda5e3177cf033a73f430f0b7",
    "homepage": "https://github.com/edi9999/jsqrcode",
    "jsnext:main": "src/index.js",
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "edi9999"
        }
    ],
    "module": "src/index.js",
    "name": "qrcode-reader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/edi9999/jsqrcode.git"
    },
    "scripts": {
        "build": "rollup -c",
        "build-and-test": "npm run build && npm test",
        "lint": "eslint src test",
        "minify": "uglifyjs dist/index.js -o dist/index.min.js --compress --mangle",
        "prepublish": "npm run build && npm run minify",
        "pretest": "npm run lint",
        "test": "mocha",
        "watch": "rollup -c -w"
    },
    "version": "0.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
