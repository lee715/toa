# Change Log

All notable changes to this project will be documented in this file starting from version **v0.10.0**.
This project adheres to [Semantic Versioning](http://semver.org/).

## [0.12.0] - 2015-06-14
### Changed

- Support `onstop` options for Toa constructor, add `context.end()` to stop request process.
- Add `app.toListener()`
- Toa constructor will not create server by default, server will be created in `app.listen()` if omit in constructor.
- Improve test and documents

### Fixed

## [0.11.1] - 2015-06-01
### Changed

- coverage test

### Fixed

---
## [0.11.0] - 2015-06-01
### Changed

- change to [JavaScript Standard Style](https://github.com/feross/standard)

### Fixed

---
## [0.10.0] - 2015-05-24
### Changed

- mount `thunk` function to context.
- remove `app.onmessage`, it become to a module `toa-pm`.
- update with `koa` v0.21.0.

### Fixed