# Changelog

## [1.2.1](https://github.com/jeffryang24/asdf-spark/compare/v1.2.0...v1.2.1) (2022-11-18)


### Bug Fixes

* **scripts:** chmod 755 for set spark_home scripts ([26a510e](https://github.com/jeffryang24/asdf-spark/commit/26a510ec23ff55a0a6125734f08aa18a6def72fd))

## [1.2.0](https://github.com/jeffryang24/asdf-spark/compare/v1.1.0...v1.2.0) (2022-11-18)


### Features

* **misc:** add set spark_home scripts ([f483e9e](https://github.com/jeffryang24/asdf-spark/commit/f483e9e87fc476fab5e29a944fc13a374dc323f9))

## [1.1.0](https://github.com/jeffryang24/asdf-spark/compare/v1.0.1...v1.1.0) (2022-10-28)


### Features

* **download:** introduce ASDF_SPARK_SKIP_VERIFICATION variable ([f9845a5](https://github.com/jeffryang24/asdf-spark/commit/f9845a5134ec7ff1f38f653720a9e138dd340834))
* **download:** verify checksum before extracting archive ([1c0985d](https://github.com/jeffryang24/asdf-spark/commit/1c0985d59f05d0e228a81f5f503607445a481a41))


### Bug Fixes

* **utils:** fix download_sha_checksum method ([6101e72](https://github.com/jeffryang24/asdf-spark/commit/6101e729ce298e7b2c55001195574f4e5b41fd46))
* **utils:** fix typo variable inside validate_sha_checksum ([c93867e](https://github.com/jeffryang24/asdf-spark/commit/c93867e27acd26ed8c05ae83912f6626e4785a33))
* **utils:** fix unbound variable from download command after refactoring ([44127c7](https://github.com/jeffryang24/asdf-spark/commit/44127c77e2b57464110be5df1cbd82d267db3dea))

## [1.0.1](https://github.com/jeffryang24/asdf-spark/compare/v1.0.0...v1.0.1) (2022-10-26)


### Bug Fixes

* **utils:** fix without-hadoop env variable pattern matching ([4fc81da](https://github.com/jeffryang24/asdf-spark/commit/4fc81da80add1c9d960592dfc5f7229af36ba456))

## 1.0.0 (2022-10-26)


### Features

* **list-all:** implement list_all_versions with unit test ([03d08e2](https://github.com/jeffryang24/asdf-spark/commit/03d08e241899dd5abef8ae2853209917e42027a4))
* **utils:** implement download and install utilities ([82eb997](https://github.com/jeffryang24/asdf-spark/commit/82eb99789c83327d405893be21cfaa2d885facf8))


### Bug Fixes

* **utils:** fix starglob when copying tools files ([90fd415](https://github.com/jeffryang24/asdf-spark/commit/90fd4159623dc6a45532bea1be0b6527e18716fd))
