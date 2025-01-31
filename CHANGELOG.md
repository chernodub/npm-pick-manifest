# Changelog

## [8.0.1](https://github.com/npm/npm-pick-manifest/compare/v8.0.0...v8.0.1) (2022-10-18)

### Dependencies

* [`9a5d485`](https://github.com/npm/npm-pick-manifest/commit/9a5d4859fcfb5bcb5cbbb309b5cc5a40dae9954e) [#73](https://github.com/npm/npm-pick-manifest/pull/73) bump npm-package-arg from 9.1.2 to 10.0.0

## [8.0.0](https://github.com/npm/npm-pick-manifest/compare/v7.0.2...v8.0.0) (2022-10-14)

### ⚠️ BREAKING CHANGES

* `npm-pick-manifest` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

* [`a3fc66c`](https://github.com/npm/npm-pick-manifest/commit/a3fc66c3f6b52cfaec20319daf64c9dbfa08d1d3) [#61](https://github.com/npm/npm-pick-manifest/pull/61) postinstall for dependabot template-oss PR (@lukekarrys)

### Dependencies

* [`cf6ddfd`](https://github.com/npm/npm-pick-manifest/commit/cf6ddfdf8ede18eed26e89f1c5dcaabb80a97913) [#70](https://github.com/npm/npm-pick-manifest/pull/70) bump npm-install-checks from 5.0.0 to 6.0.0
* [`518aba1`](https://github.com/npm/npm-pick-manifest/commit/518aba1509f85677dd08830757b43baf5a7f6d62) [#69](https://github.com/npm/npm-pick-manifest/pull/69) bump npm-normalize-package-bin from 2.0.0 to 3.0.0

## [7.0.2](https://github.com/npm/npm-pick-manifest/compare/v7.0.1...v7.0.2) (2022-08-25)


### Dependencies

* bump npm-normalize-package-bin from 1.0.1 to 2.0.0 ([#60](https://github.com/npm/npm-pick-manifest/issues/60)) ([933ce0f](https://github.com/npm/npm-pick-manifest/commit/933ce0fbd4e33a37a5ce2cefcaff03d1e1d6a2ab))

### [7.0.1](https://github.com/npm/npm-pick-manifest/compare/v7.0.0...v7.0.1) (2022-04-05)


### Dependencies

* bump npm-install-checks from 4.0.0 to 5.0.0 ([#53](https://github.com/npm/npm-pick-manifest/issues/53)) ([e425301](https://github.com/npm/npm-pick-manifest/commit/e425301ba64bcca0304dd572ca9a1b34170d6918))

## [7.0.0](https://www.github.com/npm/npm-pick-manifest/compare/v6.1.1...v7.0.0) (2022-02-10)


### ⚠ BREAKING CHANGES

* This drops support for node 10 and non-LTS versions of node 12 and node 14

### Dependencies

* @npmcli/template-oss@2.7.1 ([73e6f4f](https://www.github.com/npm/npm-pick-manifest/commit/73e6f4f9f81ceaebc327302cf4ba39c4c82b0f28))
* bump npm-package-arg from 8.1.5 to 9.0.0 ([82f45ce](https://www.github.com/npm/npm-pick-manifest/commit/82f45ceae226bcfe206361423f13166b55c1b1fe))
* update semver requirement from ^7.3.4 to ^7.3.5 ([9564d23](https://www.github.com/npm/npm-pick-manifest/commit/9564d238f67710c9f7111f99cae53d8abf30b6d3))

## [6.1.1](https://github.com/npm/npm-pick-manifest/compare/v6.0.0...v6.1.0) (2020-04-07)

* normalize package bins in returned manifest

## [6.1.0](https://github.com/npm/npm-pick-manifest/compare/v6.0.0...v6.1.0) (2020-04-07)


### Features

* add 'avoid' semver range option ([c64973d](https://github.com/npm/npm-pick-manifest/commit/c64973d63ddf6797edf41c20df641f816d30ff03))
* add avoidStrict option to strictly avoid ([c268796](https://github.com/npm/npm-pick-manifest/commit/c2687967b6294f5ce01aa6b59071e79272dc57de)), closes [#30](https://github.com/npm/npm-pick-manifest/issues/30)

## [6.0.0](https://github.com/npm/npm-pick-manifest/compare/v5.0.0...v6.0.0) (2020-02-18)


### ⚠ BREAKING CHANGES

* 'enjoyBy' is no longer an acceptable alias.

### Features

* add GitHub Actions file for ci ([8985247](https://github.com/npm/npm-pick-manifest/commit/898524727fa157f46fdf4eb0c11148ae4808226b))


### Bug Fixes

* Handle edge cases around before:Date and filtering staged publishes ([ed2f92e](https://github.com/npm/npm-pick-manifest/commit/ed2f92e7fdc9cc7836b13ebc73e17d8fd296a07e))
* remove figgy pudding ([c24fed2](https://github.com/npm/npm-pick-manifest/commit/c24fed25b8f77fbbcc3107030f2dfed55fa54222))
* remove outdated cruft from docs ([aae7ef7](https://github.com/npm/npm-pick-manifest/commit/aae7ef7625ddddbac0548287e5d57b8f76593322))
* update some missing {loose:true} semver configs ([4015424](https://github.com/npm/npm-pick-manifest/commit/40154244a3fe1af86462bc1d6165199fc3315c10))
* Use canonical 'before' config name ([029de59](https://github.com/npm/npm-pick-manifest/commit/029de59bda6d3376f03760a00efe4ac9d997c623))

## [5.0.0](https://github.com/npm/npm-pick-manifest/compare/v4.0.0...v5.0.0) (2019-12-15)


### ⚠ BREAKING CHANGES

* This drops support for node < 10.

* normalize settings, drop old nodes, update deps ([dc2e61c](https://github.com/npm/npm-pick-manifest/commit/dc2e61cc06bd19e079128e77397df7593741da50))

<a name="4.0.0"></a>
# [4.0.0](https://github.com/npm/npm-pick-manifest/compare/v3.0.2...v4.0.0) (2019-11-11)


### deps

* bump npm-package-arg to v7 ([42c76d8](https://github.com/npm/npm-pick-manifest/commit/42c76d8)), closes [/github.com/npm/hosted-git-info/pull/38#issuecomment-520243803](https://github.com//github.com/npm/hosted-git-info/pull/38/issues/issuecomment-520243803)


### BREAKING CHANGES

* this drops support for ancient node versions.



<a name="3.0.2"></a>
## [3.0.2](https://github.com/npm/npm-pick-manifest/compare/v3.0.1...v3.0.2) (2019-08-30)



<a name="3.0.1"></a>
## [3.0.1](https://github.com/npm/npm-pick-manifest/compare/v3.0.0...v3.0.1) (2019-08-28)


### Bug Fixes

* throw 403 for forbidden major/minor versions ([003286e](https://github.com/npm/npm-pick-manifest/commit/003286e)), closes [#2](https://github.com/npm/npm-pick-manifest/issues/2)



<a name="3.0.0"></a>
# [3.0.0](https://github.com/npm/npm-pick-manifest/compare/v2.2.3...v3.0.0) (2019-08-20)


### Features

* throw forbidden error when package is blocked by policy ([ad2a962](https://github.com/npm/npm-pick-manifest/commit/ad2a962)), closes [#1](https://github.com/npm/npm-pick-manifest/issues/1)


### BREAKING CHANGES

* This adds a new error code when package versions are
blocked.

PR-URL: https://github.com/npm/npm-pick-manifest/pull/1
Credit: @claudiahdz



<a name="2.2.3"></a>
## [2.2.3](https://github.com/npm/npm-pick-manifest/compare/v2.2.2...v2.2.3) (2018-10-31)


### Bug Fixes

* **enjoyBy:** rework semantics for enjoyBy again ([5e89b62](https://github.com/npm/npm-pick-manifest/commit/5e89b62))



<a name="2.2.2"></a>
## [2.2.2](https://github.com/npm/npm-pick-manifest/compare/v2.2.1...v2.2.2) (2018-10-31)


### Bug Fixes

* **enjoyBy:** rework semantics for enjoyBy ([5684f45](https://github.com/npm/npm-pick-manifest/commit/5684f45))



<a name="2.2.1"></a>
## [2.2.1](https://github.com/npm/npm-pick-manifest/compare/v2.2.0...v2.2.1) (2018-10-30)



<a name="2.2.0"></a>
# [2.2.0](https://github.com/npm/npm-pick-manifest/compare/v2.1.0...v2.2.0) (2018-10-30)


### Bug Fixes

* **audit:** npm audit fix --force ([d5ae6c4](https://github.com/npm/npm-pick-manifest/commit/d5ae6c4))


### Features

* **enjoyBy:** add opts.enjoyBy option to filter versions by date ([0b8a790](https://github.com/npm/npm-pick-manifest/commit/0b8a790))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/npm/npm-pick-manifest/compare/v2.0.1...v2.1.0) (2017-10-18)


### Features

* **selection:** allow manually disabling deprecation skipping ([0d239d3](https://github.com/npm/npm-pick-manifest/commit/0d239d3))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/npm/npm-pick-manifest/compare/v2.0.0...v2.0.1) (2017-10-18)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/npm/npm-pick-manifest/compare/v1.0.4...v2.0.0) (2017-10-03)


### Bug Fixes

* **license:** relicense project according to npm policy (#3) ([ed743a0](https://github.com/npm/npm-pick-manifest/commit/ed743a0))


### Features

* **selection:** Avoid matching deprecated packages if possible ([3fc6c3a](https://github.com/npm/npm-pick-manifest/commit/3fc6c3a))


### BREAKING CHANGES

* **selection:** deprecated versions may be skipped now
* **license:** This moves the license from CC0 to ISC and properly documents the copyright as belonging to npm, Inc.



<a name="1.0.4"></a>
## [1.0.4](https://github.com/npm/npm-pick-manifest/compare/v1.0.3...v1.0.4) (2017-06-29)


### Bug Fixes

* **npa:** bump npa version for bugfixes ([7cdaca7](https://github.com/npm/npm-pick-manifest/commit/7cdaca7))
* **semver:** use loose semver parsing for *all* ops ([bbc0daa](https://github.com/npm/npm-pick-manifest/commit/bbc0daa))



<a name="1.0.3"></a>
## [1.0.3](https://github.com/npm/npm-pick-manifest/compare/v1.0.2...v1.0.3) (2017-05-04)


### Bug Fixes

* **semver:** use semver.clean() instead ([f4133b5](https://github.com/npm/npm-pick-manifest/commit/f4133b5))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/npm/npm-pick-manifest/compare/v1.0.1...v1.0.2) (2017-05-04)


### Bug Fixes

* **picker:** spaces in `wanted` prevented match ([97a7d0a](https://github.com/npm/npm-pick-manifest/commit/97a7d0a))



<a name="1.0.1"></a>
## [1.0.1](https://github.com/npm/npm-pick-manifest/compare/v1.0.0...v1.0.1) (2017-04-24)


### Bug Fixes

* **deps:** forgot to add semver ([1876f4f](https://github.com/npm/npm-pick-manifest/commit/1876f4f))



<a name="1.0.0"></a>
# 1.0.0 (2017-04-24)


### Features

* **api:** initial implementation. ([b086912](https://github.com/npm/npm-pick-manifest/commit/b086912))


### BREAKING CHANGES

* **api:** ex nihilo
