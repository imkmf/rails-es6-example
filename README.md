Rails ES6 transpiler example, for use in a future short talk. 👍

Uses [`es6_module_transpiler-rails`](https://github.com/DavyJonesLocker/es6_module_transpiler-rails/).

Notable files:

`app/assets/javascripts/`:
- `application.js`: Loads AMD module loader and single module.
- `loader.js`: [Lightweight AMD module loader](https://github.c/ember-cli/loader.js).
- `greeter.js.es6`: Single function module for saying hello.

`app/views/pages/`:
- `index.html.erb`: Example of module loading and output to DOM.

`config/initializers`:
- `es6_transpiler.rb`: Optional configuration for ES6 output. Defaults to AMD.

Questions? [Talk to me on Twitter](http://twitter.com/imkmf).
