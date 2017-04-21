# npmdoc-travis-encrypt

#### api documentation for  [travis-encrypt (v2.1.1)](https://github.com/pwmckenna/node-travis-encrypt)  [![npm package](https://img.shields.io/npm/v/npmdoc-travis-encrypt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-travis-encrypt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-travis-encrypt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-travis-encrypt)

#### Encrypts data for use in your travis-ci yml configuration file

[![NPM](https://nodei.co/npm/travis-encrypt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/travis-encrypt)

- [https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-travis-encrypt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "travis-encrypt",
    "version": "2.1.1",
    "description": "Encrypts data for use in your travis-ci yml configuration file",
    "repository": {
        "type": "git",
        "url": "git://github.com/pwmckenna/node-travis-encrypt.git"
    },
    "scripts": {
        "test": "istanbul cover tape tests/**/*.test.js",
        "posttest": "semistandard"
    },
    "keywords": [
        ".travis.yml",
        "encryption",
        "travis",
        "travis-ci",
        "travis-pro"
    ],
    "author": "Patrick Williams <pwmckenna@gmail.com>",
    "contributors": [
        {
            "name": "Espen Hovlandsdal"
        }
    ],
    "license": "BSD-3-Clause",
    "readmeFilename": "README.md",
    "main": "lib/travis-encrypt",
    "bin": {
        "travis-encrypt": "./bin/travis-encrypt-cli.js"
    },
    "homepage": "https://github.com/pwmckenna/node-travis-encrypt",
    "bugs": "https://github.com/pwmckenna/node-travis-encrypt/issues",
    "dependencies": {
        "colors": "^1.1.2",
        "deep-property": "^1.1.0",
        "lodash.merge": "^3.3.2",
        "read-yaml": "^1.0.0",
        "travis-ci": "^2.0.3",
        "ursa": "^0.9.1",
        "write-yaml": "^0.2.2",
        "yargs": "^3.32.0"
    },
    "devDependencies": {
        "concat-stream": "^1.5.1",
        "istanbul": "^0.4.0",
        "proxyquire": "^1.7.3",
        "semistandard": "*",
        "tape": "^4.2.2"
    },
    "engines": {
        "node": ">=0.10.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
