# api documentation for  [ember-infinity (v0.2.8)](https://github.com/hhff/ember-infinity#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-infinity.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-infinity) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-infinity.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-infinity)
#### Simple, flexible infinite scroll for Ember CLI Apps.

[![NPM](https://nodei.co/npm/ember-infinity.png?downloads=true)](https://www.npmjs.com/package/ember-infinity)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-infinity/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ember-infinity_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-infinity/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ember-infinity/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ember-infinity/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugh Francis"
    },
    "bugs": {
        "url": "https://github.com/hhff/ember-infinity/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.5",
        "ember-cli-htmlbars": "^1.0.1",
        "ember-cli-version-checker": "^1.0.2",
        "ember-version-is": "0.0.3"
    },
    "description": "Simple, flexible infinite scroll for Ember CLI Apps.",
    "devDependencies": {
        "broccoli-asset-rev": "^2.2.0",
        "ember-cli": "1.13.14",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-content-security-policy": "0.4.0",
        "ember-cli-dependency-checker": "^1.1.0",
        "ember-cli-htmlbars": "^1.0.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-ic-ajax": "0.2.4",
        "ember-cli-inject-live-reload": "^1.3.1",
        "ember-cli-pretender": "0.3.2",
        "ember-cli-qunit": "^1.0.4",
        "ember-cli-release": "0.2.8",
        "ember-cli-sri": "^1.2.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "1.13.15",
        "ember-disable-prototype-extensions": "^1.0.0",
        "ember-disable-proxy-controllers": "^1.0.1",
        "ember-export-application-global": "^1.0.4",
        "ember-faker": "1.1.0",
        "ember-try": "~0.0.8"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "813a24d0828446a44d09c21fee5adf371897d8dd",
        "tarball": "https://registry.npmjs.org/ember-infinity/-/ember-infinity-0.2.8.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "http://hhff.github.io/ember-infinity/"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "94bfe50d00032c359c43a48b8e478d1fcaa0e068",
    "homepage": "https://github.com/hhff/ember-infinity#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "hhff",
            "email": "me@hughfrancis.me"
        }
    ],
    "name": "ember-infinity",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hhff/ember-infinity.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "0.2.8"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ember-infinity](#apidoc.module.ember-infinity)
1.  [function <span class="apidocSignatureSpan">ember-infinity.</span>included (app)](#apidoc.element.ember-infinity.included)
1.  [function <span class="apidocSignatureSpan">ember-infinity.</span>init ()](#apidoc.element.ember-infinity.init)
1.  string <span class="apidocSignatureSpan">ember-infinity.</span>name



# <a name="apidoc.module.ember-infinity"></a>[module ember-infinity](#apidoc.module.ember-infinity)

#### <a name="apidoc.element.ember-infinity.included"></a>[function <span class="apidocSignatureSpan">ember-infinity.</span>included (app)](#apidoc.element.ember-infinity.included)
- description and source-code
```javascript
included = function (app) {
  this.addons.forEach(function(addon){
    if (addon.name === "ember-version-is") {
      addon.included.apply(addon, [app]);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ember-infinity.init"></a>[function <span class="apidocSignatureSpan">ember-infinity.</span>init ()](#apidoc.element.ember-infinity.init)
- description and source-code
```javascript
init = function () {
  if (this._super.init) {
    this._super.init.apply(this, arguments);
  }
  checker.assertAbove(this, '0.2.0');
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
