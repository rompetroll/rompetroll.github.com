* title
 * litt om javascript
 * positive properties. positive development since 1996 (Netscape 2)
  -> 1999 ECMAscript3
  -> not much happening til 2009 ECMA 5. 2011 5.1
    -> strict mode for better error checking. but strict not supported in IE8\IE9

* shortcomings of js
 * http://garabedyan.wordpress.com/2011/07/05/crockford-javascripts-bad-and-good-parts/
 * mobil js vs web js?
 * dynamic -> depends on unit tests.
 * at the same time it's hard to unit test (installation of testing environment is hard. hard to cover all browsers)
 * too forgiving. e.g. gives you rather NaN than an error. even tries to fix syntax for you (inject semicolons)
 * event bubbling in the browser is hard
 * awful type coercion
        '' == '0' //false
        0 == '' //true
        0 == '0' //true
        false == 'false' //false
        false == '0' //false
        false == undefined //false
        false == null //false
        null == undefined //true
        " \t\r\n " == 0 //true

 * mutable, shared state
        var x = 1;
        setTimeout(function() { x = 2; }, 2);
        setTimeout(function() { console.log(x); }, 0);

  -> impossible to say what will be printed out

* shortcomings of dynamic languages

* shortcomings of interpreted languages

"12:28:19 <@  phoenix> men ser bla Uncaught TypeError: Cannot read property 'searchtop' of undefined"

* prototypes languages?

* what's desirable?
  - statically typed. compiler checked. concise
  - easy DOM interface

* but
  - should be transparent. executing compiled bytecode means the enduser can't check whats going on
  - maybe not one-fits-all solution. bytecode for enterprise stuff, something interpreted for public stuff
  - maybe something like android - shows which "rights" each site needs to function.

* attempts to make life easier for devs

  - js frameworks. jquery, dojo, mootools, prototype
    -> abstract many implementation details away
    -> handle browser incompatiblities
    -> but they basically still are javascript

  - new javascript standard ECMA6. will add new language features like classes

* compile to js

  - general pro's and con's

  - languages that compile to js
    -> GWT one of the first
    -> coffeescript
    -> Dart, TypeScript

  - roy, elm, clojurescript

  - ceylon/kotlin

  - fay

  - emscripten

  - google closure
    -> javascript to better (optimized) javascript
