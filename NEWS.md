# Changes by Version

## [Unreleased]

[Unreleased]: https://github.com/unindented/electron-installer-debian/compare/v0.7.1...master

## [0.7.1] - 2017-11-13

[0.7.1]: https://github.com/unindented/electron-installer-debian/compare/v0.7.0...v0.7.1

### Fixed

* Deduplicate dependencies when passing options via the command line (#112)

## [0.7.0] - 2017-11-09

[0.7.0]: https://github.com/unindented/electron-installer-debian/compare/v0.6.0...v0.7.0

### Added

* Support for SVG icons (#104)

### Fixed

* Update Debian dependencies for Electron apps (#105)
* Throw proper error when no description or productDescription is provided (#109)
* Append user dependencies to defaults & deduplicate (#111)

## [0.6.0] - 2017-09-27

[0.6.0]: https://github.com/unindented/electron-installer-debian/compare/v0.5.2...v0.6.0

### Added

* Support custom desktop file templates (#98)
* Support package maintainer scripts (#91)

### Fixed

* Remove lintian warnings/errors (#96)

----

For versions prior to 0.6.0, please see `git log`.
