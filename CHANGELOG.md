# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.8.3] - 2024-07-30

- sync with Dacite v1.8.1 + unreleased changes

## [1.7.4] - 2022-08-19

- fix for nested dataclasses broken after merging with dacite changes.

## [1.7.3] - 2022-08-17

- merged with updated version of dacite.

## [1.7.2] - 2021-07-09

- Fix for using a custom `from_dict` in the data classes

## [1.7.0] - 2021-07-09

- Rebranding (dacite -> tonalite)

## [1.6.0] - 2020-11-30

### Added

- Support `Type` fields

### Fixed

- Handle generic collections with implicit `Any` inner types in Python 3.9
- Fix `InitVar` with inner data classes
- Improve support for fixed length and undefined length tuples

## [1.5.1] - 2020-07-03

### Added

- Python 3.9 support

## [1.5.0] - 2020-05-02

### Added

- Add `strict_unions_match` config parameter
- Support `Tuple`

### Fixed

- The order of run type hooks in `Union`

## [1.4.0] - 2020-04-10

### Added

- Support `InitVar`

### Fixed

- Fix `Union` type hooks

## [1.3.0] - 2020-03-14

### Added

- Support `Literal`
- Support [PEP 561](https://www.python.org/dev/peps/pep-0561/)

## [1.2.1] - 2020-03-02

### Fixed

- Fix problem with a "numeric tower" and optional/new type

## [1.2.0] - 2020-01-05

### Added

- Support base classes in `cast`
- Support collections in `cast`

### Changed

- Handle "numeric tower" as described in [PEP 484](https://www.python.org/dev/peps/pep-0484/#the-numeric-tower)

## [1.1.0] - 2019-11-27

### Added

- Python 3.8 support
- `cast` config parameter

### Changed

- Validate type for generic collection fields

[1.6.0]: https://github.com/Tiqets/tonalite/compare/v1.5.1...v1.6.0
[1.5.1]: https://github.com/Tiqets/tonalite/compare/v1.5.0...v1.5.1
[1.5.0]: https://github.com/Tiqets/tonalite/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/Tiqets/tonalite/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/Tiqets/tonalite/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/Tiqets/tonalite/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/Tiqets/tonalite/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/Tiqets/tonalite/compare/v1.0.2...v1.1.0
