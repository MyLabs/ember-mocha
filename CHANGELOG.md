# Changelog

## Unreleased (2017-12-06)

#### :boom: Breaking Change
* [#164](https://github.com/emberjs/ember-mocha/pull/164) don't wrap hooks in a runloop. ([@akatov](https://github.com/akatov))

#### Committers: 1
- Dmitri Akatov ([akatov](https://github.com/akatov))


## v0.13.0 (2017-12-06)

#### :house: Internal
* [#174](https://github.com/emberjs/ember-mocha/pull/174) CI: Add Ember 2.0, 2.4 and 2.8 as test targets. ([@Turbo87](https://github.com/Turbo87))
* [#173](https://github.com/emberjs/ember-mocha/pull/173) Convert to Ember CLI addon. ([@Turbo87](https://github.com/Turbo87))
* [#172](https://github.com/emberjs/ember-mocha/pull/172) Update `broccoli-lint-eslint` and use `group` option. ([@Turbo87](https://github.com/Turbo87))
* [#171](https://github.com/emberjs/ember-mocha/pull/171) Remove `bower` publishing code. ([@Turbo87](https://github.com/Turbo87))
* [#170](https://github.com/emberjs/ember-mocha/pull/170) Use headless Chrome instead of PhantomJS. ([@Turbo87](https://github.com/Turbo87))
* [#169](https://github.com/emberjs/ember-mocha/pull/169) Add yarn lockfile and use yarn for CI. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 2
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.12.0 (2017-05-26)

#### :rocket: Enhancement
* [#123](https://github.com/emberjs/ember-mocha/pull/123) Improved async behavior deprecation message. ([@Turbo87](https://github.com/Turbo87))
* [#124](https://github.com/emberjs/ember-mocha/pull/124) README: Add instructions for a world with async/await. ([@Turbo87](https://github.com/Turbo87))

#### :bug: Bug Fix
* [#156](https://github.com/emberjs/ember-mocha/pull/156) Fix "rollup-plugin-alias" options. ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#128](https://github.com/emberjs/ember-mocha/pull/128) Ensure ember-test-helpers ^0.6.0. ([@blimmer](https://github.com/blimmer))
* [#125](https://github.com/emberjs/ember-mocha/pull/125) CI: Switch NPM deploy user to "ember-cli". ([@Turbo87](https://github.com/Turbo87))
* [#117](https://github.com/emberjs/ember-mocha/pull/117) Use Rollup to bundle files. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 2
- Ben Limmer ([blimmer](https://github.com/blimmer))
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.11.1 (2017-05-07)

#### :bug: Bug Fix
* [#150](https://github.com/emberjs/ember-mocha/pull/150) Update "ember-test-helpers" to v0.6.3. ([@Turbo87](https://github.com/Turbo87))
* [#144](https://github.com/emberjs/ember-mocha/pull/144) Reset "module" to null to prevent memory leaks. ([@Turbo87](https://github.com/Turbo87))
* [#146](https://github.com/emberjs/ember-mocha/pull/146) Update and pin "loader.js" to v4.1.0. ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#147](https://github.com/emberjs/ember-mocha/pull/147) Convert "loader.js" from bower to npm dependency. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.11.0 (2016-12-09)

#### :rocket: Enhancement
* [#122](https://github.com/emberjs/ember-mocha/pull/122) Update "mocha" and "chai" bower dependencies. ([@Turbo87](https://github.com/Turbo87))
* [#120](https://github.com/emberjs/ember-mocha/pull/120) Import "ember-mocha-adapter". ([@Turbo87](https://github.com/Turbo87))
* [#119](https://github.com/emberjs/ember-mocha/pull/119) Adjust testem config and add acceptance test. ([@Turbo87](https://github.com/Turbo87))
* [#118](https://github.com/emberjs/ember-mocha/pull/118) TravisCI: Update Node.js to 6.x. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.10.0 (2016-11-29)

#### :house: Internal
* [#114](https://github.com/emberjs/ember-mocha/pull/114) Update "ember-test-helpers" to v0.6.0-beta.1. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.9.4 (2016-11-27)

#### :rocket: Enhancement
* [#105](https://github.com/emberjs/ember-mocha/pull/105) CI: Publish tags to NPM. ([@Turbo87](https://github.com/Turbo87))

#### :bug: Bug Fix
* [#111](https://github.com/emberjs/ember-mocha/pull/111) Fix broken context cleanup. ([@Turbo87](https://github.com/Turbo87))
* [#102](https://github.com/emberjs/ember-mocha/pull/102) Export new test setup functions as globals. ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#109](https://github.com/emberjs/ember-mocha/pull/109) Remove "chai" vendor shim. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.9.3 (2016-11-23)

#### :rocket: Enhancement
* [#108](https://github.com/emberjs/ember-mocha/pull/108) mocha-module: Add upgrade guide URL to the deprecation message. ([@Turbo87](https://github.com/Turbo87))
* [#107](https://github.com/emberjs/ember-mocha/pull/107) package.json: Add "files" section. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.9.2 (2016-11-23)

#### :rocket: Enhancement
* [#106](https://github.com/emberjs/ember-mocha/pull/106) Add "Upgrade Guide" to the README. ([@Turbo87](https://github.com/Turbo87))
* [#100](https://github.com/emberjs/ember-mocha/pull/100) CI: Publish releases to "ember-mocha-builds" repo. ([@Turbo87](https://github.com/Turbo87))

#### :bug: Bug Fix
* [#101](https://github.com/emberjs/ember-mocha/pull/101) Fix tests by using the ESLint nodes correctly. ([@Turbo87](https://github.com/Turbo87))

#### :memo: Documentation
* [#96](https://github.com/emberjs/ember-mocha/pull/96) Update CHANGELOG. ([@Turbo87](https://github.com/Turbo87))
* [#97](https://github.com/emberjs/ember-mocha/pull/97) Update README. ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#94](https://github.com/emberjs/ember-mocha/pull/94) Cleanup package.json. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.9.1 (2016-09-12)

#### :house: Internal
* [#91](https://github.com/emberjs/ember-mocha/pull/91) Share Mocha's test context in setup-test-factory.. ([@dgeb](https://github.com/dgeb))

#### Committers: 1
- Dan Gebhardt ([dgeb](https://github.com/dgeb))


## v0.9.0 (2016-09-12)

#### :rocket: Enhancement
* [#84](https://github.com/emberjs/ember-mocha/pull/84) New testing API. ([@Turbo87](https://github.com/Turbo87))
* [#76](https://github.com/emberjs/ember-mocha/pull/76) Adjust "mocha" dependency to allow 2.3, 2.4, ... releases. ([@Turbo87](https://github.com/Turbo87))

#### :memo: Documentation
* [#86](https://github.com/emberjs/ember-mocha/pull/86) Add changelog file. ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#90](https://github.com/emberjs/ember-mocha/pull/90) Preserve suite context in outer test function. ([@dgeb](https://github.com/dgeb))
* [#89](https://github.com/emberjs/ember-mocha/pull/89) Share Mocha's test context.. ([@dgeb](https://github.com/dgeb))
* [#88](https://github.com/emberjs/ember-mocha/pull/88) Use predefined ESLint test generator. ([@Turbo87](https://github.com/Turbo87))
* [#85](https://github.com/emberjs/ember-mocha/pull/85) Replace JSHint with ESLint. ([@Turbo87](https://github.com/Turbo87))
* [#83](https://github.com/emberjs/ember-mocha/pull/83) Update NPM dependencies. ([@Turbo87](https://github.com/Turbo87))

#### Committers: 2
- Dan Gebhardt ([dgeb](https://github.com/dgeb))
- Tobias Bieniek ([Turbo87](https://github.com/Turbo87))


## v0.8.1 (2016-02-01)

#### :rocket: Enhancement
* [#47](https://github.com/emberjs/ember-mocha/pull/47) Update ember test helpers for Ember 2.0.0-beta.3.. ([@Robdel12](https://github.com/Robdel12))
* [#43](https://github.com/emberjs/ember-mocha/pull/43) Update ember-test-helpers. ([@sly7-7](https://github.com/sly7-7))

#### :bug: Bug Fix
* [#72](https://github.com/emberjs/ember-mocha/pull/72) Ensure builds of ember-test-helpers are properly transpiled.. ([@rwjblue](https://github.com/rwjblue))
* [#48](https://github.com/emberjs/ember-mocha/pull/48) remove resetViews from 'it'. ([@jeffreybiles](https://github.com/jeffreybiles))

#### :house: Internal
* [#45](https://github.com/emberjs/ember-mocha/pull/45) Remove usage of deprecated `Ember.keys`. ([@tstirrat](https://github.com/tstirrat))

#### Committers: 5
- Jeffrey Biles ([jeffreybiles](https://github.com/jeffreybiles))
- Robert DeLuca ([Robdel12](https://github.com/Robdel12))
- Robert Jackson ([rwjblue](https://github.com/rwjblue))
- Sylvain MINA ([sly7-7](https://github.com/sly7-7))
- Tim Stirrat ([tstirrat](https://github.com/tstirrat))


## v0.8.10 (2016-02-01)

#### :bug: Bug Fix
* [#72](https://github.com/emberjs/ember-mocha/pull/72) Ensure builds of ember-test-helpers are properly transpiled.. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([rwjblue](https://github.com/rwjblue))


## v0.8.6 (2015-10-27)

#### :rocket: Enhancement
* [#65](https://github.com/emberjs/ember-mocha/pull/65) Expose chai configuration object. ([@mupkoo](https://github.com/mupkoo))

#### Committers: 1
- Mirko Akov ([mupkoo](https://github.com/mupkoo))


## v0.8.4 (2015-10-02)

#### :rocket: Enhancement
* [#62](https://github.com/emberjs/ember-mocha/pull/62) Update ember-test-helpers to 0.5.11. ([@mattmcmanus](https://github.com/mattmcmanus))
* [#59](https://github.com/emberjs/ember-mocha/pull/59) Add shim for context. ([@SaladFork](https://github.com/SaladFork))

#### Committers: 2
- Elad Shahar ([SaladFork](https://github.com/SaladFork))
- Matt McManus ([mattmcmanus](https://github.com/mattmcmanus))


## v0.8.3 (2015-09-13)

#### :rocket: Enhancement
* [#58](https://github.com/emberjs/ember-mocha/pull/58) Update minimum version of ember-test-helpers.. ([@rwjblue](https://github.com/rwjblue))
* [#57](https://github.com/emberjs/ember-mocha/pull/57) Make `beforeEach` and `afterEach` use Ember.run. ([@cowboyd](https://github.com/cowboyd))

#### Committers: 2
- Charles Lowell ([cowboyd](https://github.com/cowboyd))
- Robert Jackson ([rwjblue](https://github.com/rwjblue))


## v0.8.2 (2015-08-27)

#### :rocket: Enhancement
* [#55](https://github.com/emberjs/ember-mocha/pull/55) Update ember-test-helpers minimum version.. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([rwjblue](https://github.com/rwjblue))


## v0.8.0 (2015-06-19)

#### :rocket: Enhancement
* [#39](https://github.com/emberjs/ember-mocha/pull/39) Update ember-test-helpers to 0.5.0.. ([@eriktrom](https://github.com/eriktrom))

#### Committers: 1
- Erik Trom ([eriktrom](https://github.com/eriktrom))


## v0.6.3 (2015-05-13)

#### :rocket: Enhancement
* [#35](https://github.com/emberjs/ember-mocha/pull/35) Bump ember-test-helpers, mocha, and chai. ([@dgeb](https://github.com/dgeb))

#### Committers: 1
- Dan Gebhardt ([dgeb](https://github.com/dgeb))


## v0.6.1 (2015-04-04)

#### :rocket: Enhancement
* [#32](https://github.com/emberjs/ember-mocha/pull/32) Update to use newer ember-mocha-adapter. ([@ef4](https://github.com/ef4))

#### Committers: 1
- Edward Faulkner ([ef4](https://github.com/ef4))


## v0.6.0 (2015-03-24)

#### :rocket: Enhancement
* [#27](https://github.com/emberjs/ember-mocha/pull/27) Expose Chai helpers for custom assertions. ([@dfreeman](https://github.com/dfreeman))
* [#29](https://github.com/emberjs/ember-mocha/pull/29) Update ember-test-helpers. ([@dfreeman](https://github.com/dfreeman))

#### Committers: 1
- Dan Freeman ([dfreeman](https://github.com/dfreeman))


## v0.4.4 (2015-02-22)

#### :rocket: Enhancement
* [#23](https://github.com/emberjs/ember-mocha/pull/23) Add chai and mocha ES6 shims.. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([rwjblue](https://github.com/rwjblue))


## v0.4.1 (2015-02-08)

#### :house: Internal
* [#20](https://github.com/emberjs/ember-mocha/pull/20) Switch from broccoli-cli to ember-cli.. ([@dgeb](https://github.com/dgeb))
* [#18](https://github.com/emberjs/ember-mocha/pull/18) Use git-repo-version instead of git-repo-info directly.. ([@dgeb](https://github.com/dgeb))
* [#19](https://github.com/emberjs/ember-mocha/pull/19) Upgrade ember to 1.10.0 and remove handlebars.. ([@dgeb](https://github.com/dgeb))

#### Committers: 1
- Dan Gebhardt ([dgeb](https://github.com/dgeb))


## v0.2.2 (2015-01-25)

#### :house: Internal
* [#12](https://github.com/emberjs/ember-mocha/pull/12) Add broccoli-cli for running tests. ([@backspace](https://github.com/backspace))

#### Committers: 1
- Buck Doyle ([backspace](https://github.com/backspace))


## v0.2.1 (2014-12-11)

#### :rocket: Enhancement
* [#9](https://github.com/emberjs/ember-mocha/pull/9) toString method of wrapper of it should forward to callback.toString ins.... ([@lyonlai](https://github.com/lyonlai))

#### Committers: 1
- Yun Lai ([lyonlai](https://github.com/lyonlai))


## v0.1.3 (2014-11-26)

#### :rocket: Enhancement
* [#7](https://github.com/emberjs/ember-mocha/pull/7) Add mocha to generated bower.json.. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([rwjblue](https://github.com/rwjblue))


## v0.1.2 (2014-11-26)

#### :rocket: Enhancement
* [#6](https://github.com/emberjs/ember-mocha/pull/6) preserve mocha test context in both setup and assertion blocks. ([@cowboyd](https://github.com/cowboyd))
* [#4](https://github.com/emberjs/ember-mocha/pull/4) allow `it`, `xit`, `it.skip` and `it.only` forms.. ([@cowboyd](https://github.com/cowboyd))

#### :bug: Bug Fix
* [#5](https://github.com/emberjs/ember-mocha/pull/5) Globalized fixes. ([@cowboyd](https://github.com/cowboyd))
* [#2](https://github.com/emberjs/ember-mocha/pull/2) call to it caused infinite loop in global build. ([@cowboyd](https://github.com/cowboyd))

#### Committers: 1
- Charles Lowell ([cowboyd](https://github.com/cowboyd))
