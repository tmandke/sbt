  [1586]: https://github.com/sbt/sbt/pull/1586
  [1590]: Https://github.com/sbt/sbt/pull/1590
  [@jsuereth]: https://github.com/jsuereth
  
  
### Improvements

* Add developers key

### Fixes with compatibility implications

* Maven artifact dependencies now limit their transitive dependencies to "compile" rather than "every configuration"
  if no `master` configuration is found.  [#1586][1586] by [@jsuereth][@jsuereth]
