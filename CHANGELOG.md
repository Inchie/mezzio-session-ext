# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 0.1.4 - 2018-02-28

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zendframework/zend-expressive-session-ext#1](https://github.com/zendframework/zend-expressive-session-ext/pull/1)
  fixes a problem that occurs when a requested session does not resolve to an
  existing session and/or an existing session with empty data, leading to
  creation of new sessions on each request.

## 0.1.3 - 2018-02-24

### Added

- [zendframework/zend-expressive-session-ext#5](https://github.com/zendframework/zend-expressive-session-ext/pull/5) adds
  support for the ^1.0.0alpha1 release of mezzio-session.

## 0.1.2 - 2017-12-12

### Added

- [zendframework/zend-expressive-session-ext#3](https://github.com/zendframework/zend-expressive-session-ext/pull/3) adds
  support for the 1.0-dev and 1.0 releases of mezzio-session.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.1.1 - 2017-10-10

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Fixes session regeneration under PHP 7.2 so that it will not raise warnings.

## 0.1.0 - 2017-10-10

Initial release.

### Added

- Everything.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.
