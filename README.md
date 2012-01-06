snack.js
========

_... because sometimes, all you need is a snack._

Features
--------

### Tiny!

- ~3.4kb! (minified, gzipped)

### Elements

- Use any selector engine. Ships with multiple builds (QSA, [Qwery](https://github.com/ded/qwery), [Slick](https://github.com/mootools/slick), [Sizzle](http://sizzlejs.com/))
- Several element methods
- API to add more element methods

### Events

- Cross-browser DOMContentLoaded (domready)
- Cross-browser DOM events
- Event Delegation (with or without a selector engine)

### Pub/Sub

- Publisher objects for application communication

### AJAX

- Cross-browser AJAX
- JSONP

### Utilities

- Shallow object merge with `snack.extend`
- Prototypal inheritance with `snack.beget`
- A few other utilities (only those snack uses)

Documentation
-------------

Snack is very well documented. In the repository is a docs folder.
Simply open `docs/index.html` in your browser or visit the [Snack Homepage](http://snackjs.com).

Contributing / Testing / Building Snack
---------------------------------------

### Submodules (selector engines)

Because Snack ships with several selector engines, there are submodules
for each one.  You'll need to first update them to build or test Snack:

From the root of the repository:

    $ git submodule init
    $ git submodule update

### Tests

The tests require [node](http://nodejs.org/) >= 0.4.6, [npm](http://npmjs.org) >= 1.0.0, and submodules to be updated (see above).

To run the tests, install dependencies and fire up the server (used for all
the ajax stuff).

    $ npm install .
    $ node server.js

### Building

Build snack like so:

    $ ./build

The tests do not require you to build snack.

Inspiration and code snatching from:
------------------------------------

- [MooTools](http://mootools.net) (c) Valerio Proietti, MIT license
- [jQuery](http://jquery.com)  (c) John Resig, Dual license MIT or GPL Version 2
- [Zepto](https://github.com/madrobby/zepto) (c) Thomas Fuchs, MIT License
- [ContentLoaded](http://javascript.nwbox.com/ContentLoaded/) (c) Diego Perini, MIT License

License
-------

[MIT Style](http://creativecommons.org/licenses/MIT/) license.

Copyright
---------

Copyright (c) [Ryan Florence](http://ryanflorence.com)