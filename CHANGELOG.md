# Changelog

## 1.0.5 - 2026-01-17

### Changed

- Updated YAML array format in `settings.yaml`.
    - Updated `:php_error_reporting` value.
- Updated `Vagrantfile` by adding local variables.
    - Modernized path in the `YAML.load_file()` call.
- Replaced `FORWARDED_PORT_80` variable with `HOST_HTTP_PORT` in 3 files.
    - Updated `provision.sh`, `adminer.conf`, `virtualhost.conf` with new variable name.
- Modified the version section of `provision.sh` for the section title and the Apache version output.
- Updated the last section of `README.md`.

## 1.0.4 - 2025-10-13

### Added

- Added `CHANGELOG.md`

### Changed

- Updated `README.md`

### Fixed

- PHP repositories for Ubuntu 20-04 (Focal) are no longer available from `packages.sury.org`
    - Removed `sury` PHP repository
    - Reverted to original Ubuntu 20-04 PHP version 7.4
- Updated Adminer to version 5+ plugin code and files.

## 1.0.3 - 2023-08-10

### Fixed

- Fixed Ruby in `Vagrantfile`

## 1.0.2 - 2023-01-15

### Added

- Added Adminer plugins.

## 1.0.1 - 2022-05-06

### Changed

- Updated MariaDB repositories.
- Fixed Adminer password lock.
- Updated `bash_aliases`, `virtualhost.conf`, `adminer.conf`, README.
- Moved box name to `settings.yaml`.
- Hard-coded `/vagrant/config` in `provision.sh`.
- Changed `/dev/null`.
- Moved Git & Subversion together.

## 1.0.0 - 2021-04-26

_First release_
