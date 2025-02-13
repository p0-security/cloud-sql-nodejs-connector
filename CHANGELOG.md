# Changelog

## [1.0.0](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.5.1...v1.0.0) (2023-09-27)


### Features

* add force refresh on connection errors ([#195](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/195)) ([993d5d8](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/993d5d893454d2768d138a3edca714f4468a443d))


### Bug Fixes

* add .js ext. for mjs imports in .d.ts files ([#215](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/215)) ([a998db6](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/a998db6c740e72591738a86a27deae4f4c20af09))
* https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/134 ([8988b45](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/8988b45e2652c51700cf87435362836c15131125))
* https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/146 ([8988b45](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/8988b45e2652c51700cf87435362836c15131125))
* retry failed google-auth-library requests ([#181](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/181)) ([8988b45](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/8988b45e2652c51700cf87435362836c15131125))
* silent refresh errors on active connection ([#219](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/219)) ([41a8e79](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/41a8e799915f815d73f0b75e488c149301ed2431))


### Miscellaneous Chores

* set release version to v1.0.0 ([#221](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/221)) ([c24482c](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/c24482c1d09bd322afa267b7b220174acf0ffdd7))

## [0.5.1](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.5.0...v0.5.1) (2023-08-08)


### Bug Fixes

* release v0.5.1 ([#178](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/178)) ([151ff55](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/151ff553a162c85662659ebb1e9b2bafbea3ba65))

## [0.5.0](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.4.0...v0.5.0) (2023-07-11)


### Features

* add support to PSC ip type ([#150](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/150)) ([d3929cd](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/d3929cd2e8f6d62d7b2eeff5277d9f81f3a42eae))

## [0.4.0](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.3.0...v0.4.0) (2023-06-13)


### ⚠ BREAKING CHANGES

* remove returned ssl property

### Features

* add sqlserver support ([ab3dc67](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/ab3dc6768dfdf526df9b1b2bcb1307d1cfef34be))


### Bug Fixes

* auth type should be optional in typescript ([bed3424](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/bed3424e4c1b8cc185a74deedaa6f4a6531fc131))
* make ipType optional ([0f3f75e](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/0f3f75e13aeba53201044c4ebdf38e213ad1ac84))


### Code Refactoring

* remove returned ssl property ([c0c4572](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/c0c4572f8eedfad13f87d9e2841a1f951f96600a))


### Miscellaneous Chores

* release 0.4.0 ([#145](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/145)) ([9561694](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/9561694b7c1d20847e8d9b34803163e47bc33e66))

## [0.3.0](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.2.0...v0.3.0) (2023-05-09)


### ⚠ BREAKING CHANGES

* update `IpAdressesTypes` to `IpAddressTypes` ([#94](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/94))
* rename type to ipType ([#83](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/83))

### Features

* support automatic IAM authentication ([#78](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/78)) ([ad95065](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/ad95065b8260d81fcc7642adfcac4074e789a43e))


### Bug Fixes

* throw error when conflicting connection settings for same instance ([#84](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/84)) ([1c7b3d1](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/1c7b3d120265323ae7d1cf3ad0e45fdc709a9889))
* user-agent version number ([511ccd8](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/511ccd8ea48d830977a1fdb4584e6e4d24640164))


### Code Refactoring

* rename type to ipType ([#83](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/83)) ([fcf66fa](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/fcf66fa41ae4fefcffc490b445dd9bb14c456be5))
* update `IpAdressesTypes` to `IpAddressTypes` ([#94](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/94)) ([e38d392](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/e38d392add7fb90f76cc25915d3591af9c705ba1))


### Miscellaneous Chores

* release 0.3.0 ([#109](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/109)) ([72ccb47](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/72ccb478d9bb613f1b12d6789b6b74ae6b3c333e))

## [0.2.0](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.1.3...v0.2.0) (2023-04-11)


### Features

* add mysql support ([9316804](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/93168049995520bc290368b0530fd768d052db38))


### Bug Fixes

* add default keep-alive delay ([c3eb3c9](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/c3eb3c96aa2452be5d64a125080d05308fd1a27f))

## [0.1.3](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.1.2...v0.1.3) (2023-03-22)


### Bug Fixes

* esm dist target ([8320dec](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/8320decd8ae4926f70527c4ff7933b4e0e3589f1))

## [0.1.2](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.1.1...v0.1.2) (2023-03-15)


### Bug Fixes

* publishing build system ([1819179](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/1819179195fb4a84a1ce878e092d8070c3defc3d))

## [0.1.1](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/compare/v0.1.0...v0.1.1) (2023-03-14)


### Bug Fixes

* **docs:** update install instruction ([#48](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/48)) ([ecaede2](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/ecaede2b6c041c2e0f006d73e27578c3586790fd))

## 0.1.0 (2023-03-14)


### Features

* add Connector.getOptions method ([7bb9456](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/7bb94564cc95d5e6a64b0006d53c66de752184c2))


### Bug Fixes

* **deps:** update dependency @googleapis/sqladmin to v7 ([a31beaf](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/a31beafa030f05cfd01c761ca71a4eadddf06975))


### Miscellaneous Chores

* release 0.1.0 ([#35](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/issues/35)) ([6fa46ac](https://github.com/GoogleCloudPlatform/cloud-sql-nodejs-connector/commit/6fa46ac014bbdc84fd09d8097aebbab76f08dbd7))
