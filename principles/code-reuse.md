# Code reuse

Stratic does not reinvent the wheel. If we have to, it probably means that we're
doing too much. See [Unix](unix.md).

Instead, we strive to interoperate with existing tools. This leads to more
collaboration and less work for everyone involved. If we end up inventing our
own ecosystem, with our own set of plugins and conventions, we've failed.

A pithy way of saying this is, "it's all userland". In other words, there's no
"Stratic core" that _must_ be used or adhered to. Instead, Stratic itself
operates entirely within the userland of some other "core" (specifically,
[gulp](https://gulpjs.com/)). There's absolutely nothing special about any
Stratic module; they are all regular gulp plugins.

## Adopted

2018-01-28

## Author

AJ Jordan
