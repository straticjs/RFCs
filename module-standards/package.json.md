# package.json

Every module needs a high-quality `package.json`. In addition to the
required fields, good `package.json` files _always_ have:

1. A `repository` field and a `bugs` field
2. A `homepage` field (it's okay for this to point to the README,
   which is what `npm init` generates)
3. A valid SPDX identifier in the `license` field
4. A `keywords` field that always contains the `stratic` keyword and
   additionally contains the `gulpplugin` keyword if it handles gulp
   streams (which most Stratic modules will)

## stratic-lint-module support

Minimal (can check for the `stratic` keyword)

## Adopted

2017-07-07

## Author

AJ Jordan
