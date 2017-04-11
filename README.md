# test coverage for  [xo (v0.18.1)](https://github.com/sindresorhus/xo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-xo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xo.svg)](https://travis-ci.org/npmtest/node-npmtest-xo)
#### JavaScript happiness style linter ❤️

[![NPM](https://nodei.co/npm/xo.png?downloads=true)](https://www.npmjs.com/package/xo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xo/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xo/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-xo/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-xo/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-xo%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xo/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xo/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-xo%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "email": "sindresorhus@gmail.com",
        "url": "sindresorhus.com"
    },
    "bin": {
        "xo": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/xo/issues"
    },
    "dependencies": {
        "arrify": "^1.0.0",
        "debug": "^2.2.0",
        "deep-assign": "^1.0.0",
        "eslint": "^3.18.0",
        "eslint-config-xo": "^0.18.0",
        "eslint-formatter-pretty": "^1.0.0",
        "eslint-plugin-ava": "^4.2.0",
        "eslint-plugin-import": "^2.0.0",
        "eslint-plugin-no-use-extend-native": "^0.3.2",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-unicorn": "^2.1.0",
        "get-stdin": "^5.0.0",
        "globby": "^6.0.0",
        "has-flag": "^2.0.0",
        "lodash.isequal": "^4.4.0",
        "meow": "^3.4.2",
        "multimatch": "^2.1.0",
        "parse-gitignore": "^0.3.1",
        "path-exists": "^3.0.0",
        "pkg-conf": "^2.0.0",
        "resolve-cwd": "^1.0.0",
        "resolve-from": "^2.0.0",
        "update-notifier": "^2.1.0",
        "xo-init": "^0.5.0"
    },
    "description": "JavaScript happiness style linter ❤️",
    "devDependencies": {
        "ava": "*",
        "coveralls": "^2.11.9",
        "eslint-config-xo-react": "^0.10.0",
        "eslint-plugin-react": "^6.3.0",
        "execa": "^0.6.1",
        "nyc": "^10.1.2",
        "pify": "^2.3.0",
        "proxyquire": "^1.7.3",
        "temp-write": "^3.1.0",
        "xo": "github:sindresorhus/xo#v0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "529bb1cbd612f200221d76df90639d5c88cedf54",
        "tarball": "https://registry.npmjs.org/xo/-/xo-0.18.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "cli.js",
        "options-manager.js",
        "config"
    ],
    "gitHead": "d82bdea1dcccdf27bb8358516150034f7a8e2c41",
    "homepage": "https://github.com/sindresorhus/xo#readme",
    "keywords": [
        "❤️",
        "cli-app",
        "cli",
        "xo",
        "xoxo",
        "hugs",
        "kisses",
        "happy",
        "happiness",
        "code",
        "quality",
        "style",
        "lint",
        "linter",
        "jscs",
        "jshint",
        "jslint",
        "eslint",
        "validate",
        "code style",
        "standard",
        "strict",
        "check",
        "checker",
        "verify",
        "enforce",
        "hint",
        "simple"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jamestalmage",
            "email": "james@talmage.io"
        },
        {
            "name": "marionebl",
            "email": "root@mario-nebl.de"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        }
    ],
    "name": "xo",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/xo.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && nyc ava"
    },
    "version": "0.18.1",
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
