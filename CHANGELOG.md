# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [v0.2.0] - 2017-02-08

### Added

- Now `cast::Error` implements the `std::error::Error` trait among other traits
  like `Display`, `Clone`, etc.

### Changed

- [breaking-change] This crate now depends on the `std` crate by default but you
  can make it `no_std` by opting out of the `std` Cargo feature.

## v0.1.0 - 2016-02-07

Initial release

[Unreleased]: https://github.com/japaric/cast.rs/compare/v0.2.0...HEAD
[v0.2.0]: https://github.com/japaric/cast.rs/compare/v0.1.0...v0.2.0