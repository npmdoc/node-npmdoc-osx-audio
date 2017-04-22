# npmdoc-osx-audio

#### api documentation for  osx-audio (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-osx-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-osx-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-osx-audio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-osx-audio)

#### Access to Mac OS X Audio I/O as streams. Only input is supported so far.

[![NPM](https://nodei.co/npm/osx-audio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osx-audio)

- [https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osx-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-osx-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-osx-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "osx-audio",
    "version": "1.0.0",
    "description": "Access to Mac OS X Audio I/O as streams. Only input is supported so far.",
    "main": "index.js",
    "engines": {
        "node": ">=0.10.30"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "install": "node-gyp rebuild"
    },
    "os": [
        "darwin"
    ],
    "gypfile": true,
    "author": "Nathan Wittstock <nate@milkandtang.com>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/fardog/node-osx-audio.git"
    },
    "keywords": [
        "audio",
        "coreaudio",
        "sound",
        "recording",
        "input",
        "stream",
        "osx",
        "corefoundation"
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "debug": "^2.0.0",
        "nan": "^2.3.3"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
