v1.0.3 / 2016-12-03
===================

  * fix node.js version in package.json #36

v1.0.2 / 2016-11-28
===================

  * fix proxy null check #32

v1.0.1 / 2016-11-25
===================

  * improve mock exception messages #31

v1.0.0 / 2016-11-24
===================

  * fix reference path in readme
  * fix postinstall build #26
  * enable npm install github #26
  * remove bower
  * log to console when Proxy not available in a test #20
  * add dynamic mocking #20
  * update readme to reflect previous api change
  * [BREAKING CHANGE] change api to return mock interfaces
  * use reference equality for implicit object matcher #28
  * verify invocation order #29
  * allow implicit object value param as setup matcher #28
  * proper mock reset #27
  * repackage typemoq as an UMD module #25
  * target method overridden by corresponding return func #21
  * clone target instance at mock instantiation
  * replace Underscore with Lodash
  * rename 'output' to 'typemoq' #24
  * enable chaining of callback and verifiable #23
  * change Exception to extend from Error #22
  * update to typescript 2.0

v0.3.3 / 2016-08-28
===================

  * add support for mock reset #18
  * add string values to MockExceptionReason

v0.3.2 / 2016-07-22
===================

  * improve mockability of getters/setters

v0.3.1 / 2016-07-17
===================

  * fix require underscore statement
  * update readme with latest changes since 0.2.0
  * change predicate matcher return type to T
  * add predicate matcher #14
  * change .verifiable to take a Times param #13
  * revert param order of GobalMock.ofInstance/ofType
  * add ES6 testing for node.js #7
  * Merge pull request #15 from rkostrzewski/master
  * set GlobalMock.globalName default equal to Mock.name
  * use function.name when available
  * Enabled ES6 classes support
  * change some interfaces to type aliases
  * update readme to use 'let' declarations
  * change 'var' to 'let' declarations

v0.2.0 / 2016-06-12
===================

  * support TypeScript 1.6 npm package typing resolving #4

v0.1.1 / 2016-06-06
===================

  * record/replay in the same order (not reversed as before)
  * support for record/replay scenarios
  * readme minor updates
  * correction in doc for node install

v0.1.0 / 2016-05-26
===================

  * improve runtime support for browser and node
  * update doc - add nuget install info
  * support TypeScript 1.6 npm package typing resolving
  * Merge pull request #6 from lowkay/master
  * Fix ExtractProxyCall from mutating the context
  * Merge pull request #2 from the-vk/master
  * Fixed exception thrown in Exception.toString()

v0.0.6 / 2015-09-10
===================

  * prep bower packaging
  * export TypeMoq object for node.js
  * change prop desc handling in global scope
  * add global objects mocking
  * bundle up output with dependencies
  * update package info
  * first working prototype

