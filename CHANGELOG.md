# Changelog

## [3.2.5] 2020-02-09

### Fixed
 - Formatting strings with hash inside
 - Fixed getattr call formatting bug
 - Fixed 'extends' formatting bug

## [3.2.4] 2020-02-06

### Fixed
 - Fixed parent block comments in if-elif-else
 - Fixed parentheses handling in formatter
 - Improved fromatter's dedent lookup
 - Fixed 'extends' bug in grammar
 - Fixed grammar - types allow dots now

## [3.2.3] 2020-02-04

### Fixed
 - Type inference in grammar
 - Improved linter exec user experience
 - Fixed linter hanging on config file not present

## [3.2.2] 2020-02-03

### Fixed
 - Missing grammar file added

## [3.2.1] 2020-02-02

### Fixed
 - Package metadata

## [3.2.0] 2020-02-02

### Added
 - Grammar
 - Parser (`gdparse`)
 - Linter (`gdlint`) with some basic checks
 - Formatter (`gdformat`) which should work for most of real-life scenarios
