# NODE_DEBUG= support

Since Stratic focuses on exposing clean internals, Stratic modules
should use [node-debug][] to help people with understanding what's
actually going on in said internals.

The name passed to `debug` should be prefixed with `stratic:` and end
with the module name minus the `stratic-` prefix. If _really_
necessary, you can add a third subtype with a third `:` (but do this
sparingly). For example:

* `stratic-date-in-path` becomes `stratic:date-in-path`
* `stratic-posts-to-index` might conceivably have
  `stratic:posts-to-index:months`, `stratic:posts-to-index:years`,
  etc.

 [node-debug]: https://www.npmjs.com/package/debug

## stratic-lint-module support

None

## Adopted

2017-07-24

## Author

AJ Jordan
