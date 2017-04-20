# npmdoc-markdown-to-json

#### api documentation for  markdown-to-json (v0.5.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-markdown-to-json.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-markdown-to-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-markdown-to-json.svg)](https://travis-ci.org/npmdoc/node-npmdoc-markdown-to-json)

#### Extracts YAML front matter from markdown files to a single JSON string or file.

[![NPM](https://nodei.co/npm/markdown-to-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/markdown-to-json)

- [https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-markdown-to-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "markdown-to-json",
    "version": "0.5.1",
    "description": "Extracts YAML front matter from markdown files to a single JSON string or file.",
    "author": {
        "name": "Scott Stanfield"
    },
    "contributors": [
        {
            "name": "Capi Etheriel"
        }
    ],
    "keywords": [
        "yaml",
        "markdown",
        "json"
    ],
    "main": "./lib/m2j.js",
    "scripts": {
        "test": "TZ='America/Tijuana' mocha -u bdd"
    },
    "bin": {
        "m2j": "./bin/m2j"
    },
    "repository": "git://github.com/scottstanfield/markdown-to-json",
    "engines": {
        "node": "*"
    },
    "license": "BSD",
    "dependencies": {
        "commander": "^2.9.0",
        "lodash.truncate": "^4.4.2",
        "moment": "^2.17.1",
        "yaml-front-matter": "^3.4.0"
    },
    "devDependencies": {
        "eslint": "^3.15.0",
        "eslint-config-google": "^0.7.1",
        "glob": "*",
        "mocha": "*",
        "should": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
