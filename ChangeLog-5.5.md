# Changes in PHPUnit 5.5

All notable changes of the PHPUnit 5.5 release series are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [5.5.1] - 2016-08-17

### Fixed

* Fixed [#1961](https://github.com/sebastianbergmann/phpunit/issues/1961): XSD schema in 5.x does not validate
* Incorrect warning about missing `@covers` annotation is no longer shown when `@coversNothing` is used together with `forceCoversAnnotation=true`

## [5.5.0] - 2016-08-05

### Added

* Added the `PHPUnit\Framework\TestCase::createPartialMock()` method for creating partial test doubles using best practice defaults
* Merged [#2203](https://github.com/sebastianbergmann/phpunit/pull/2203): Ability to `--list-suites` for a given configuration

### Changed

* An `AssertionError` raised by an `assert()` in the tested code now causes the test to be interpreted as a failure instead of an error

[5.5.1]: https://github.com/sebastianbergmann/phpunit/compare/5.5.0...5.5.1
[5.5.0]: https://github.com/sebastianbergmann/phpunit/compare/5.4...5.5.0

