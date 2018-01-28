# Data property conventions

When modules use data - either by exposing it themselves or using data exposed
by another module - they should use properties on `file.data`. This is the gulp
ecosystem convention (many existing tools also expect this) and is a natural
place to put it.

Modules should also take care to expose any information they may have determined
internally, especially if it's hard to determine downstream.

For example, `stratic-posts-to-index` exposes `file.data.indexType` because this
is useful for templating (e.g. for modifying the `<title>` based on what index
type is being rendered). It's also very difficult and expensive to determine
this information unless the data is provided by `stratic-posts-to-index`.

## Adopted

2018-01-28

## Author

AJ Jordan
