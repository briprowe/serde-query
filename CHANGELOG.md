# Changelog

## Unreleased

## [0.1.3] - 2020-09-13

### Added

* Added `serde_query::Deserialize` derive macro that directly generates `serde::Deserialize`.
* Generated `Query` type is now a `#[repr(transparent)]` wrapper around the target type.
  It implements `Deref`/`DerefMut` now.

## [0.1.2] - 2020-09-05

### Fixed

* Correctly handles non-`&str` keys.

## [0.1.1] - 2020-09-05

### Added

* Allow index queries.
* Allow field queries with special characters.

## [0.1.0] - 2020-09-03

### Added

* Added `DeserializeQuery` derive macro. Currently it handles only map accesses.

[0.1.3]: https://github.com/pandaman64/serde-query/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/pandaman64/serde-query/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/pandaman64/serde-query/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/pandaman64/serde-query/releases/tag/v0.1.0