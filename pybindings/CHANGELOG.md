# Changelog

## Unreleased

## Added
- `add_edge` method to `VecGraph` class.

## [0.1.2](https://github.com/dfacoet/quizx/compare/quizx-py-v0.1.1...quizx-py-v0.1.2) (2025-05-02)


### Features

* `Phase` struct ([#31](https://github.com/dfacoet/quizx/issues/31)) ([ff4fd88](https://github.com/dfacoet/quizx/commit/ff4fd88a41061cabb022e0d26e7e853009a5aae3))
* Brought use_cats and get_nterms into the scope of the python bindings ([#42](https://github.com/dfacoet/quizx/issues/42)) ([5c91ab2](https://github.com/dfacoet/quizx/commit/5c91ab2537d9f08c6eb6f8568042f6e71f975464))
* Rust decoder for `.qgraph` files (pyzx/quantomatic graph format) ([#22](https://github.com/dfacoet/quizx/issues/22)) ([cdc73ad](https://github.com/dfacoet/quizx/commit/cdc73adec40509beb9b9873302eaccf19b790d19))
* Scalar serialization and pyzx interop ([#33](https://github.com/dfacoet/quizx/issues/33)) ([b19f3cf](https://github.com/dfacoet/quizx/commit/b19f3cfb7447542b6620b50962223d27b18d9d72))
* Small update to the Python API ([#76](https://github.com/dfacoet/quizx/issues/76)) ([a7c3080](https://github.com/dfacoet/quizx/commit/a7c3080886c1978fbc0b201af88b32d64919faa3))


### Bug Fixes

* gadget fusion ([#40](https://github.com/dfacoet/quizx/issues/40)) ([e8ef605](https://github.com/dfacoet/quizx/commit/e8ef605e71e4ccdb03a7f3934e77a4b764541f08))
* Lints and warnings ([#16](https://github.com/dfacoet/quizx/issues/16)) ([c2d127c](https://github.com/dfacoet/quizx/commit/c2d127c07874c16b763edf7aeafdffe12a83ffaf))
* make qubit and row into floats (closes [#93](https://github.com/dfacoet/quizx/issues/93)) ([0da3b64](https://github.com/dfacoet/quizx/commit/0da3b64b6a7ad63a690c9c389a04a4e140ec3b55))
* Move rust bindings to a `quizx._quizx` submodule ([#20](https://github.com/dfacoet/quizx/issues/20)) ([5f68df6](https://github.com/dfacoet/quizx/commit/5f68df6fe6d171484996c60b82eb944984aa794a))
* **python:** Implement add_edge in VecGraph ([#102](https://github.com/dfacoet/quizx/issues/102)) ([9718a97](https://github.com/dfacoet/quizx/commit/9718a973ed647cd6ec6961029d42f51fb3a24112))
* sdist build config ([#73](https://github.com/dfacoet/quizx/issues/73)) ([91aea91](https://github.com/dfacoet/quizx/commit/91aea912ebf36b622166b97ca19ed2f0328aeaea))


### Documentation

* Add pypi badges to the readmes ([#84](https://github.com/dfacoet/quizx/issues/84)) ([2d03128](https://github.com/dfacoet/quizx/commit/2d031280d630ebb68b0bc97bd8e71c6629d1319d))

## [0.1.1](https://github.com/zxcalc/quizx/compare/quizx-py-v0.1.0...quizx-py-v0.1.1) (2025-02-21)


### Features

* Bumped `pyzx` version to `0.9.0` ([#95](https://github.com/zxcalc/quizx/issues/95))

### Documentation

* Add pypi badges to the readmes ([#84](https://github.com/zxcalc/quizx/issues/84)) ([2d03128](https://github.com/zxcalc/quizx/commit/2d031280d630ebb68b0bc97bd8e71c6629d1319d))

## 0.1.0 (2024-10-30)


This is the initial experimental release of `quizx`.


----

This is the changelog for the `quizx` python library.
For the changelog of the `quizx` rust library, see the separate [`CHANGELOG.md`](https://github.com/zxcalc/quizx/blob/master/CHANGELOG.md) file.
