# [2.3.0](https://github.com/atom-community/sync-settings/compare/v2.2.0...v2.3.0) (2020-02-14)


### Features

* add extra file glob settings ([#483](https://github.com/atom-community/sync-settings/issues/483)) ([426ea4d](https://github.com/atom-community/sync-settings/commit/426ea4d4a1046eeca2b94fdc981ae2914e2807c1))

# [2.2.0](https://github.com/atom-community/sync-settings/compare/v2.1.0...v2.2.0) (2020-02-11)


### Bug Fixes

* use key-path-helper ([#482](https://github.com/atom-community/sync-settings/issues/482)) ([46c0007](https://github.com/atom-community/sync-settings/commit/46c000754dae98b3580baa5382a91033114644f2))


### Features

* add only sync community packages setting ([#480](https://github.com/atom-community/sync-settings/issues/480)) ([bb11814](https://github.com/atom-community/sync-settings/commit/bb11814abc7b9521eedcb5e6df1fc55e5903b7e5))

# [2.1.0](https://github.com/atom-community/sync-settings/compare/v2.0.3...v2.1.0) (2020-02-10)


### Bug Fixes

* use busy-signal if available ([#475](https://github.com/atom-community/sync-settings/issues/475)) ([058de3e](https://github.com/atom-community/sync-settings/commit/058de3efd5b207142650a4211606f3c667a50499))


### Features

* add setting to install latest version of packages ([#478](https://github.com/atom-community/sync-settings/issues/478)) ([b3c1f0c](https://github.com/atom-community/sync-settings/commit/b3c1f0cd623b8df7bdaa096259ebf8d1c9b39114))
* add syncThemes setting ([#479](https://github.com/atom-community/sync-settings/issues/479)) ([9ca9177](https://github.com/atom-community/sync-settings/commit/9ca91774eccb40b2400ca24aa155b58d310f8bb5))

## [2.0.3](https://github.com/atom-community/sync-settings/compare/v2.0.2...v2.0.3) (2020-02-10)


### Bug Fixes

* remove correct packages ([ab1e54b](https://github.com/atom-community/sync-settings/commit/ab1e54bb58ecaa2d47ebf4fc9a986fbdc2032185))

## [2.0.2](https://github.com/atom-community/sync-settings/compare/v2.0.1...v2.0.2) (2020-02-10)


### Bug Fixes

* back up settings ([ff0ac1b](https://github.com/atom-community/sync-settings/commit/ff0ac1be5afada83e4f3b91dc60626a05ccd033c))
* mark files with only whitespace as not found ([343c43c](https://github.com/atom-community/sync-settings/commit/343c43ce614edc5ff7ca0f2cc52429122b7a8054))
* notify backup up to date ([abe8298](https://github.com/atom-community/sync-settings/commit/abe8298a9a705b114829ef6d57ab44ae59964d1b))
* warn about backing up config.cson ([cb8ea45](https://github.com/atom-community/sync-settings/commit/cb8ea4521588f629f9c42a0a9d8560b86ebe9636))

## [2.0.1](https://github.com/atom-community/sync-settings/compare/v2.0.0...v2.0.1) (2020-02-08)


### Bug Fixes

* remove atom-space-pen-view ([#468](https://github.com/atom-community/sync-settings/issues/468)) ([9732372](https://github.com/atom-community/sync-settings/commit/9732372e4fc093f272ba4327dc38f99ca4e1d7b3))

## v2.0.0 (2020-02-06)
* Rewrite code in JavaScript and update dependencies [#464](https://github.com/atom-community/sync-settings/pull/464)

## v0.8.6 (2018-03-26)
* Fix handling of property names with a dot. Closes [#358](https://github.com/atom-community/sync-settings/pull/424)
* Ensure fetched files contain valid JSON before using them to restore config. Closes [#315, #362, #368, #384, #413, #416, #417](https://github.com/atom-community/sync-settings/pull/422)

## v0.8.5 (2018-02-22)
* Fix reading property 'substr' of undefined. Closes [#409](https://github.com/atom-community/sync-settings/pull/410)

## v0.8.4 (2018-02-21)
* Support Atom 1.25 and newer. Closes [#403](https://github.com/atom-community/sync-settings/pull/403) and [#405](https://github.com/atom-community/sync-settings/pull/405)
* Redact parts of the personal access token from debug message. Closes [#395](https://github.com/atom-community/sync-settings/pull/395)
* Fallback to GIST_ID environment variable. Closes [#367](https://github.com/atom-community/sync-settings/pull/407)

## v0.8.3 (2017-08-28)
* Fix configu option to remove obsolete packages. Closes [#379](https://github.com/atom-community/sync-settings/pull/379)
* Prioritize package settings over GITHUB_TOKEN env variable. Closes [#366](https://github.com/atom-community/sync-settings/pull/374)

## v0.8.2 (2017-06-13)
* Remove obsolete packages. Closes [#91](https://github.com/atom-community/sync-settings/pull/338)
* Utilise GITHUB_TOKEN env variable. Closes [#343](https://github.com/atom-community/sync-settings/pull/357)
* Add support for init.js. Closes [#331](https://github.com/atom-community/sync-settings/pull/339)

## v0.8.1 (2016-12-29)
* Restore keeps reinstalling disabled packages. Closes [#328](https://github.com/atom-community/sync-settings/issues/328)

## v0.8.0 (2016-12-08)
* Remove Analytics. Closes [#321](https://github.com/atom-community/sync-settings/issues/321)
* Avoid exception when editing Analytics User Id. Closes [#320](https://github.com/atom-community/sync-settings/issues/320)
* Catch SyntaxError for JSON.parse calls. Closes [#319](https://github.com/atom-community/sync-settings/issues/319)
* Reduce debug messages on the console. Closes [#312](https://github.com/atom-community/sync-settings/issues/312)
* Add notifications while installing packages, limit concurrent installations. Closes [#311](https://github.com/atom-community/sync-settings/issues/311)
* Sync disabled packages too. Closes [#310](https://github.com/atom-community/sync-settings/issues/310)
* Allow syncing git-installed packages. Closes [#299](https://github.com/atom-community/sync-settings/issues/299)
* Update dependencies, switch back to github from github4. Closes [#283](https://github.com/atom-community/sync-settings/issues/283)
* Add keywords to package manifest. Closes [#235](https://github.com/atom-community/sync-settings/issues/235)

## v0.7.2 (2016-03-11)
* New release from new location

## v0.7.1 (2016-03-11)
* This package has been moved to [Atom Community](https://github.com/atom-community) organization. Closes [#227](https://github.com/atom-community/sync-settings/issues/227)

## v0.7.0 (2016-03-07)
* Allow synchronizing some settings of this package. Closes [#193](https://github.com/atom-community/sync-settings/pull/193)
* Fix restoring settings of type color. Fixes [#180](https://github.com/atom-community/sync-settings/issues/180)
* Improve documentation to use private gists. Closes [#190](https://github.com/atom-community/sync-settings/issues/190)
* Add option to blacklist specific configuration values. Closes [#165](https://github.com/atom-community/sync-settings/issues/165)
* Trim GistID and personal access token. Fixes [#153](https://github.com/atom-community/sync-settings/issues/153)
* Add fork command. Closes [#187](https://github.com/atom-community/sync-settings/pull/187)
* Use platform specific folder for temporary files during testing. Closes [185](https://github.com/atom-community/sync-settings/pull/185)
* Add option to mute latest backup message on startup [182](https://github.com/atom-community/sync-settings/pull/182)
* Check for mandatory settings at startup. Closes [140](https://github.com/atom-community/sync-settings/pull/140)
* Proxy support. Closes [142](https://github.com/atom-community/sync-settings/issues/142)
* Improve documentation how to run sync settings commands. Closes [172](https://github.com/atom-community/sync-settings/pull/172)
* Add option to customize Gist description. Closes [163](https://github.com/atom-community/sync-settings/issues/163)
* Improve documentation on settings in config.cson. Closes [161](https://github.com/atom-community/sync-settings/issues/161)
* Improve documentation how to run the unit tests. Closes [139](https://github.com/atom-community/sync-settings/pull/139)
* Use deterministic package order for reasonable diffs. Fixes [149](https://github.com/atom-community/sync-settings/pull/149)
* Fix uncaught TypeError. Fixes [135](https://github.com/atom-community/sync-settings/issues/135)
* Restore check backup command. Fixes [116](https://github.com/atom-community/sync-settings/pull/116)

## v0.6.0 (2015-08-01)
* Check for updated backup. Closes [#81](https://github.com/atom-community/sync-settings/issues/81)
* New menu option to open the gist with external browser. Closes [#87](https://github.com/atom-community/sync-settings/issues/87)
* Track usage. Closes [#82](https://github.com/atom-community/sync-settings/issues/82)

## v0.5.0 (2015-06-26)
* Fixed snippets not applied. Fixes [#36](https://github.com/atom-community/sync-settings/issues/36)
  * Please note that this issue created a redundant file called `snippets.coffee`
* Rename Upload/Download to Backup/Restore. Fixes [#50](https://github.com/atom-community/sync-settings/issues/50)
* Remove keymaps. Closes [#69](https://github.com/atom-community/sync-settings/issues/69)
* Improve package load time. Fixes [#33](https://github.com/atom-community/sync-settings/issues/33)
* Settings for which things to sync. Closes [#54](https://github.com/atom-community/sync-settings/issues/54)

## v0.4.0 (2015-06-10)
* Added default contents for empty files
* Fix writing contents to extra files

## v0.3.0 (2015-06-09)
* Defer package activation until first upload/download
* Added link to uploaded gist in success notification
* Fixed deprecations
* Update atom engine semver

## v0.2.2 (2015-03-05)
* Fixed deprecations
* Fixed [#23](https://github.com/atom-community/sync-settings/issues/23)
* Added extra files setting

## v0.2.1 (2015-01-24)
* Added notifications
* Fixed deprecations

## v0.2.0 (2015-01-06)
* Sync user styles
* Sync init
* Sync snippets
* Remove sensitive sync-settings setting data

## v0.1.0 (2014-08-03)
* First Release
