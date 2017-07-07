# Monorepo antipattern

Some projects with many modules choose to manage all the modules
within one repository and publish all of them at once. See for
example [Babel][] and [Pug][].

This is considered an antipattern because it encourages intellectual
laziness when designing things. When everything is guaranteed to be in
sync in the same repository, the designer doesn't prioritize
extensibility and flexibility. Having one repository per module
encourages the designer to strongly prioritize interoperability with
other modules because if they didn't, it would create a lot more work
for everyone.

## Adopted

2017-07-07

## Author

AJ Jordan

 [Babel]: https://github.com/babel/babel
 [Pug]: https://github.com/pugjs/pug
