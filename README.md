# npmdoc-cheerio-httpcli

#### api documentation for  [cheerio-httpcli (v0.6.11)](https://github.com/ktty1220/cheerio-httpcli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cheerio-httpcli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cheerio-httpcli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cheerio-httpcli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cheerio-httpcli)

#### http client module with cheerio & iconv(-lite) & promise

[![NPM](https://nodei.co/npm/cheerio-httpcli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cheerio-httpcli)

- [https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cheerio-httpcli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ktty1220"
    },
    "bugs": {
        "url": "https://github.com/ktty1220/cheerio-httpcli/issues"
    },
    "dependencies": {
        "@types/cheerio": "^0.17.31",
        "@types/node": "^6.0.62",
        "async": "^2.1.4",
        "cheerio": "^0.22.0",
        "colors": "^1.1.2",
        "constants": "0.0.2",
        "foreach": "^2.0.5",
        "he": "^1.1.1",
        "iconv-lite": "^0.4.15",
        "jschardet": "^1.4.1",
        "object-assign": "^4.1.1",
        "os-locale": "~1.4.0",
        "prettyjson": "^1.2.1",
        "request": "^2.79.0",
        "require-uncached": "^1.0.3",
        "rsvp": "^3.3.3",
        "spawn-sync": "^1.0.15",
        "tough-cookie": "^2.3.2",
        "type-of": "^2.0.1",
        "valid-url": "^1.0.9",
        "yargs": "^6.6.0"
    },
    "description": "http client module with cheerio & iconv(-lite) & promise",
    "devDependencies": {
        "dev-null": "^0.1.1",
        "eslint": "^3.14.1",
        "espower-loader": "^1.2.0",
        "intelli-espower-loader": "^1.0.1",
        "isstream": "^0.1.2",
        "istanbul": "^0.4.5",
        "jscs": "^3.0.7",
        "leasot": "^4.3.0",
        "mocha": "^3.2.0",
        "mocha-clean": "^1.0.0",
        "node-static": "^0.7.9",
        "power-assert": "^1.4.2",
        "pre-commit": "^1.2.2",
        "random-string": "^0.1.2",
        "strip-ansi": "^3.0.1",
        "yargs": "^6.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "61294a839efdcf59a21220bb8748be95352e6f6b",
        "tarball": "https://registry.npmjs.org/cheerio-httpcli/-/cheerio-httpcli-0.6.11.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "d2abc64b684eb38fb4b0c74fe38315d0cbaf42d6",
    "homepage": "https://github.com/ktty1220/cheerio-httpcli#readme",
    "keywords": [
        "cheerio",
        "http",
        "dom",
        "scrape"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ktty1220"
        }
    ],
    "name": "cheerio-httpcli",
    "optionalDependencies": {},
    "pre-commit": [
        "lint"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/ktty1220/cheerio-httpcli.git"
    },
    "scripts": {
        "cov": "istanbul cover -x index.js -x testrunner.js testrunner.js -- -R nyan || true",
        "cs": "jscs lib test example || true",
        "dep": "depcheck --parsers=*.js:es6,*.json:json --ignores=iconv-lite,os-locale,espower-loader || true",
        "lint": "eslint lib test example --ext .js",
        "test": "node testrunner.js || true",
        "todo": "leasot -S lib/**/**/* test/** example/** || true"
    },
    "typings": "./index.d.ts",
    "version": "0.6.11",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
