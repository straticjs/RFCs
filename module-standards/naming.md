# Naming

Stratic modules should always start with the prefix `stratic-`
(although there may be times where exceptions make sense, such as for
`generator-stratic`). This helps with consistency.

The rest of the name should be a description of what the module does
in the imperative mood (e.g. `stratic-lint-module` instead of
`stratic-module-linter`). When in doubt, ask yourself if it makes
sense at the end of the sentence, "the module's job is to
[convert]..."

For example:

> The module's job is to lint modules.

Or, for `stratic-posts-to-index`:

> The module's job is to convert posts to indexes.

## stratic-lint-module support

None

## Adopted

2017-07-07

## Author

AJ Jordan
