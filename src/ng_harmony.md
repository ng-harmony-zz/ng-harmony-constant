# Ng-Harmony
============

## Development

![Harmony = 6 + 7;](logo.png "Harmony - Fire in my eyes")

Why?

    * Easily retain event-names via your editors autocomplete
    * Have a decent standard for further lib use of UX-Events (UX-decorator)

## Concept

It helps to be able to provide a UXEVENT.EVENTNAME `constant!!` instead of a
"typo-errorable" string `variable!`

Use it in conjunction with

* [literate-programming](http://npmjs.org/packages/literate-programming "click for npm-package-homepage") to write markdown-flavored literate JS, HTML and CSS
* [jspm](https://www.npmjs.com/package/jspm "click for npm-package-homepage") for a nice solution to handle npm-modules with ES6-Module-Format-Loading ...

## Files

This serves as literate-programming compiler-directive

[build/index.js](#Compilation "save:")

You can extend these literate-programming directives here ... the manual is (on jostylr@github/literate-programming)[https://github.com/jostylr/literate-programming]

## Compilation

To bring eventing to the Controller ng-harmony introduces zepto.js since angularjs
doesn't expose it's own Eventing. The include jQuery-Lite doesn't provide the
necessary tools either ...

The UXEVENT constant holds the `hardcoded` proper event strings of zepto.js

```javascript
export class UXEVENT {}
UXEVENT.HOVER = "hover";
UXEVENT.BLUR = "blur";
UXEVENT.CHANGE = "change";
UXEVENT.CLICK = "click";
UXEVENT.DBLCLICK = "dblclick";
UXEVENT.FOCUSIN = "focusin";
UXEVENT.FOCUSOUT = "focusout";
UXEVENT.KEYDOWN = "keydown";
UXEVENT.KEYPRESS = "keypress";
UXEVENT.KEYUP = "keyup";
UXEVENT.MOUSEDOWN = "mousedown";
UXEVENT.MOUSEENTER = "mouseenter";
UXEVENT.MOUSELEAVE = "mouseleave";
UXEVENT.MOUSEOUT = "mouseout";
UXEVENT.MOUSEOVER = "mouseover";
UXEVENT.MOUSEUP = "mouseup";
UXEVENT.MOUSEMOVE = "mousemove";
UXEVENT.RESIZE = "resize";
UXEVENT.SCROLL = "scroll";
UXEVENT.SELECT = "select";
UXEVENT.SUBMIT = "submit";
UXEVENT.UNLOAD = "unload";
```

## CHANGELOG

*v0.1.0* Zepto Event List (zepto.js is used in the ng-harmony-controller component)
