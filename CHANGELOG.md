# Changelog

## [7.4.0](https://github.com/npm/node-semver/compare/v7.3.8...v7.4.0) (2023-04-10)

### Features

* [`113f513`](https://github.com/npm/node-semver/commit/113f51312a1a6b6aa50d4f9486b4fde21782c1f5) [#532](https://github.com/npm/node-semver/pull/532) identifierBase parameter for .inc (#532) (@wraithgar, @b-bly)
* [`48d8f8f`](https://github.com/npm/node-semver/commit/48d8f8fa63bf6e35db70ff840b6da1a51596a5a8) [#530](https://github.com/npm/node-semver/pull/530) export new RELEASE_TYPES constant (@hcharley)

### Bug Fixes

* [`940723d`](https://github.com/npm/node-semver/commit/940723d22bca824993627c45ac30dd3d2854b8cd) [#538](https://github.com/npm/node-semver/pull/538) intersects with v0.0.0 and v0.0.0-0 (#538) (@wraithgar)
* [`aa516b5`](https://github.com/npm/node-semver/commit/aa516b50b32f5a144017d8fc1b9efe0540963c91) [#535](https://github.com/npm/node-semver/pull/535) faster parse options (#535) (@H4ad)
* [`61e6ea1`](https://github.com/npm/node-semver/commit/61e6ea1e9b7af01baf19ab0c0a63c8e3ebfac97c) [#536](https://github.com/npm/node-semver/pull/536) faster cache key factory for range (#536) (@H4ad)
* [`f8b8b61`](https://github.com/npm/node-semver/commit/f8b8b619e71746a47852a9d301f3087ab311444f) [#541](https://github.com/npm/node-semver/pull/541) optimistic parse (#541) (@H4ad)
* [`796cbe2`](https://github.com/npm/node-semver/commit/796cbe29b06d102e1b16f3ed78eaba210ece951e) [#533](https://github.com/npm/node-semver/pull/533) semver.diff prerelease to release recognition (#533) (@wraithgar, @dominique-blockchain)
* [`3f222b1`](https://github.com/npm/node-semver/commit/3f222b144033525ca9f8a2ce5bc6e02f0401881f) [#537](https://github.com/npm/node-semver/pull/537) reuse comparators on subset (#537) (@H4ad)
* [`f66cc45`](https://github.com/npm/node-semver/commit/f66cc45c6e82eebb4b5b51af73e7b8dcaeda7e21) [#539](https://github.com/npm/node-semver/pull/539) faster diff (#539) (@H4ad)

### Documentation

* [`c5d29df`](https://github.com/npm/node-semver/commit/c5d29df6f75741fea27fffe3b88c9c3b28e3ca73) [#530](https://github.com/npm/node-semver/pull/530) Add "Constants" section to README (@hcharley)

## [7.3.8](https://github.com/npm/node-semver/compare/v7.3.7...v7.3.8) (2022-10-04)

### Bug Fixes

* [`d8ef32c`](https://github.com/npm/node-semver/commit/d8ef32cee7a7e34310838f32451c9bcf52956b64) [#383](https://github.com/npm/node-semver/pull/383) add support for node.js esm auto exports (#383) (@MylesBorins)

### Documentation

* [`7209b14`](https://github.com/npm/node-semver/commit/7209b14ccd7ca35b9a1077a0b67d9ce884fe6d00) [#477](https://github.com/npm/node-semver/pull/477) update range.js comments to clarify the caret ranges examples (#477) (@amitse)

### [7.3.7](https://github.com/npm/node-semver/compare/v7.3.6...v7.3.7) (2022-04-11)


### Bug Fixes

* allow node >=10 ([85b269a](https://github.com/npm/node-semver/commit/85b269a90806713d2a41e8e990b0ea6bc274b171))
* **bin:** get correct value from arg separated by equals ([#449](https://github.com/npm/node-semver/issues/449)) ([4ceca76](https://github.com/npm/node-semver/commit/4ceca76729c577166395f19172854cbbcce3cec1)), closes [#431](https://github.com/npm/node-semver/issues/431)
* ensure SemVer instance passed to inc are not modified ([#427](https://github.com/npm/node-semver/issues/427)) ([f070dde](https://github.com/npm/node-semver/commit/f070dde0cc22894ac254e281cb36a79ab790272d))
* inc prerelease with numeric preid ([#380](https://github.com/npm/node-semver/issues/380)) ([802e161](https://github.com/npm/node-semver/commit/802e16174fe2a704dba16e97891ce36dc4f2ad76))


### Dependencies

* revert to lru-cache@6 ([22ae54d](https://github.com/npm/node-semver/commit/22ae54d66c2dec8200947066dbb9c33bb729b8a8))

### [7.3.6](https://github.com/npm/node-semver/compare/v7.3.5...v7.3.6) (2022-04-05)


### Bug Fixes

* https://github.com/npm/node-semver/issues/329 ([cb1ca1d](https://github.com/npm/node-semver/commit/cb1ca1d5480a6c07c12ac31ba5f2071ed530c4ed))
* properly escape dots in `GTE0` regexes ([#432](https://github.com/npm/node-semver/issues/432)) ([11494f1](https://github.com/npm/node-semver/commit/11494f1446a907c8fa5d9cfbc9fab04d553311f5))
* replace deprecated String.prototype.substr() ([#445](https://github.com/npm/node-semver/issues/445)) ([e2d55e7](https://github.com/npm/node-semver/commit/e2d55e79f0d288ea88c0e0ba6620fe5636a4a552))
* replace regex used to split ranges ([#434](https://github.com/npm/node-semver/issues/434)) ([9ab7b71](https://github.com/npm/node-semver/commit/9ab7b717dd7848c639b8ce3366d2241d430cdad2))


### Documentation

* clarify * range behavior ([cb1ca1d](https://github.com/npm/node-semver/commit/cb1ca1d5480a6c07c12ac31ba5f2071ed530c4ed))


### Dependencies

* lru-cache@7.4.0 ([#442](https://github.com/npm/node-semver/issues/442)) ([9a3064c](https://github.com/npm/node-semver/commit/9a3064c242cdce3c1c39cae37a83d93ead363b37))
* tap@16.0.0 ([#439](https://github.com/npm/node-semver/issues/439)) ([60cbb3f](https://github.com/npm/node-semver/commit/60cbb3fd4a4d32979f3aa0a2aa4e185753106545))

## 7.3.0

* Add `subset(r1, r2)` method to determine if `r1` range is entirely
  contained by `r2` range.

## 7.2.3

* Fix handling of `includePrelease` mode where version ranges like `1.0.0 -
  2.0.0` would include `3.0.0-pre` and not `1.0.0-pre`.

## 7.2.2

* Fix bug where `2.0.0-pre` would be included in `^1.0.0` if
  `includePrerelease` was set to true.

## 7.2.0

* Add `simplifyRange` method to attempt to generate a more human-readable
  range expression that is equivalent to a supplied range, for a given set
  of versions.

## 7.1.2

* Remove fancy lazy-loading logic, as it was causing problems for webpack
  users.

## 7.1.0

* Add `require('semver/preload')` to load the entire module without using
  lazy getter methods.

## 7.0.0

* Refactor module into separate files for better tree-shaking
* Drop support for very old node versions, use const/let, `=>` functions,
  and classes.

## 6.3.0

* Expose the token enum on the exports

## 6.2.0

* Coerce numbers to strings when passed to semver.coerce()
* Add `rtl` option to coerce from right to left

## 6.1.3

* Handle X-ranges properly in includePrerelease mode

## 6.1.2

* Do not throw when testing invalid version strings

## 6.1.1

* Add options support for semver.coerce()
* Handle undefined version passed to Range.test

## 6.1.0

* Add semver.compareBuild function
* Support `*` in semver.intersects

## 6.0

* Fix `intersects` logic.

    This is technically a bug fix, but since it is also a change to behavior
    that may require users updating their code, it is marked as a major
    version increment.

## 5.7

* Add `minVersion` method

## 5.6

* Move boolean `loose` param to an options object, with
  backwards-compatibility protection.
* Add ability to opt out of special prerelease version handling with
  the `includePrerelease` option flag.

## 5.5

* Add version coercion capabilities

## 5.4

* Add intersection checking

## 5.3

* Add `minSatisfying` method

## 5.2

* Add `prerelease(v)` that returns prerelease components

## 5.1

* Add Backus-Naur for ranges
* Remove excessively cute inspection methods

## 5.0

* Remove AMD/Browserified build artifacts
* Fix ltr and gtr when using the `*` range
* Fix for range `*` with a prerelease identifier
