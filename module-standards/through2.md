# through2 for streams

Stratic modules that handle streams (mostly gulp plugins) should
use [through2][] to abstract away the stream setup. Using through2:

* Uses Streams3 everywhere
  (see: [Why I don't use Node's core 'stream' module][rvagg])
* Ensures consistency between modules, so once the reader is familiar
  with through2 they'll be able to read most Stratic modules
* Makes Stratic module code less noisy
* Eliminates bugs in subclassing setup (since this is done internally
  in through2)

 [through2]: https://www.npmjs.com/package/through2
 [rvagg]: https://r.va.gg/2014/06/why-i-dont-use-nodes-core-stream-module.html

## stratic-lint-module support

None

## Adopted

2017-07-24

## Author

AJ Jordan
