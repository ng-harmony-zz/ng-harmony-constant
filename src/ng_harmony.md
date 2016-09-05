# Ng-Harmony
============

## Development

![Harmony = 6 + 7;](logo.png "Harmony - Fire in my eyes")

Please concoct a rather useful gist here ...

## Concept

This extra lib to ng-harmony will serve the purpose of *[...]*

Use it in conjunction with

* [literate-programming](http://npmjs.org/packages/literate-programming "click for npm-package-homepage") to write markdown-flavored literate JS, HTML and CSS
* [jspm](https://www.npmjs.com/package/jspm "click for npm-package-homepage") for a nice solution to handle npm-modules with ES6-Module-Format-Loading ...

## Files

This serves as literate-programming compiler-directive

[build/index.js](#Compilation "save:")

You can extend these literate-programming directives here ... the manual is (on jostylr@github/literate-programming)[https://github.com/jostylr/literate-programming]

## Compilation

Now just start coding/commenting as you go ...

You might want to
* code on the fly
* use literate-programming as a full paradigm of some super-constructor
* switch back and forth between the dev/master and gh-pages branches and use TDD/BDD

You'll probably want to import some base class of ng-harmony itself

```javascript
import { Harmony, Controller, Service } from "ng-harmony/ng-harmony";
```

```javascript
export class YourClass extends Harmony {
    constructor(...args) {
        super(...args);
    }
}
YourClass.$inject = "$http";
YourClass.$register = {
    "yourNgModule": {
        "name": "YourRegisteredClassName",
        "type": "controller/service/factory/component"
    }
}
```

## CHANGELOG

*v0.1.0* Introducing cool features
