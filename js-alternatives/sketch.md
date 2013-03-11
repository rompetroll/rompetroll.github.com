* what's desirable?
  - statically typed. compiler checked. concise

* but
  - should be transparent. executing compiled bytecode means the enduser can't check whats going on
  - maybe not one-fits-all solution. bytecode for enterprise stuff, something interpreted for public stuff
  - maybe something like android - shows which "rights" each site needs to function.

* attempts to make life easier for devs

  - js frameworks. jquery, dojo, mootools, prototype
    -> abstract many implementation details away
    -> handle browser incompatiblities
    -> but they basically still are javascript
    -> latest jsquery replaces callbacks with promises.

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
