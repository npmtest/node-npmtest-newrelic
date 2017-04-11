# test coverage for  [newrelic (v1.38.2)](http://github.com/newrelic/node-newrelic)  [![npm package](https://img.shields.io/npm/v/npmtest-newrelic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-newrelic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-newrelic.svg)](https://travis-ci.org/npmtest/node-npmtest-newrelic)
#### New Relic agent

[![NPM](https://nodei.co/npm/newrelic.png?downloads=true)](https://www.npmjs.com/package/newrelic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-newrelic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-newrelic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-newrelic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-newrelic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-newrelic/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-newrelic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-newrelic/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-newrelic/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-newrelic/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-newrelic/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-newrelic%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-newrelic/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-newrelic%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-newrelic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-newrelic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-newrelic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "New Relic Node.js agent team",
        "email": "nodejs@newrelic.com"
    },
    "bin": {
        "newrelic-naming-rules": "./bin/test-naming-rules.js"
    },
    "bugs": {
        "url": "https://github.com/newrelic/node-newrelic/issues"
    },
    "bundleDependencies": [
        "concat-stream",
        "https-proxy-agent",
        "json-stringify-safe",
        "readable-stream",
        "semver"
    ],
    "contributors": [
        {
            "name": "Saxon D'Aubin",
            "email": "saxon@newrelic.com",
            "url": "http://newrelic.com"
        },
        {
            "name": "Forrest L Norvell",
            "email": "forrest@newrelic.com",
            "url": "http://newrelic.com/"
        },
        {
            "name": "Jacob Groundwater",
            "email": "jacob@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Wraithan",
            "email": "wmcdonald@newrelic.com",
            "url": "Chris McDonald"
        },
        {
            "name": "Michael Hayes",
            "email": "mhayes@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Bryan Clement",
            "email": "bclement@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Jeff Olfert",
            "email": "jolfert@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Wilson Bilkovich",
            "email": "wbilkovich@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Jonathan Merrill",
            "email": "jmerrill@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Martin Kuba",
            "email": "mkuba@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Tim Krajcar",
            "email": "tkrajcar@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Eric Wang",
            "email": "ewang@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Natalie Wolfe",
            "email": "nwolfe@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Seth Shober",
            "email": "sshober@newrelic.com",
            "url": "https://newrelic.com"
        }
    ],
    "dependencies": {
        "concat-stream": "^1.5.0",
        "https-proxy-agent": "^0.3.5",
        "json-stringify-safe": "^5.0.0",
        "readable-stream": "^1.1.13",
        "semver": "^5.3.0"
    },
    "description": "New Relic agent",
    "devDependencies": {
        "async": "^2.1.4",
        "eslint": "^2.9.0",
        "mocha": "*",
        "tap": "^9.0.3"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "c14cda98fc682be7fe770996c65beca88c4b6884",
        "tarball": "https://registry.npmjs.org/newrelic/-/newrelic-1.38.2.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "bbbeaa6dfd3cce9e1785b4567f89438e2b56afe9",
    "homepage": "http://github.com/newrelic/node-newrelic",
    "keywords": [
        "apm",
        "performance",
        "monitoring",
        "instrumentation",
        "debugging",
        "profiling"
    ],
    "licenses": [
        {
            "type": "proprietary",
            "url": "https://raw.github.com/newrelic/node-newrelic/master/LICENSE"
        }
    ],
    "maintainers": [
        {
            "name": "lykkin",
            "email": "bclement01@gmail.com"
        }
    ],
    "name": "newrelic",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/newrelic/node-newrelic.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.38.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
