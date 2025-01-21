# [1.6.0](https://github.com/thingworx-field-work/QueryBuilderWidgetTWX/compare/v1.5.0...v1.6.0) (2025-01-21)


### Features

* add IN operator for number inputs ([#47](https://github.com/thingworx-field-work/QueryBuilderWidgetTWX/issues/47)) ([cc517e4](https://github.com/thingworx-field-work/QueryBuilderWidgetTWX/commit/cc517e4c287b9d87613efa1da25c9c751d575049))

# [1.5.0](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/compare/v1.4.1...v1.5.0) (2024-10-01)


### Features

* **date_format:** allow the user to specify if time should be selectable in the date time picker by specifying a `DatePickerFormat` with  no time component ([be3a040](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/be3a040d8c543453ccf0849ebb49dc04a868ded3))

## [1.4.1](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/compare/v1.4.0...v1.4.1) (2024-09-17)


### Bug Fixes

* when the data is bound from another widget, it would not update the query fields ([dbc8be4](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/dbc8be472143756cd9270d840251cecf83c46e0a))

# [1.4.0](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/compare/v1.3.2...v1.4.0) (2024-07-16)


### Features

* allow a custom date format to be specified for the dates ([#45](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/issues/45)) ([6a1d443](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/6a1d4436ff069fb98027b3ece4eca2ace4c3e7dc))

## [1.3.2](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/compare/v1.3.1...v1.3.2) (2023-11-30)


### Bug Fixes

* trigger a new release, this time including a good production build ([b700460](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/b700460f6b94fb92e3f207f134c56e6f9db0854b))

## [1.3.1](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/compare/v1.3.0...v1.3.1) (2023-11-30)


### Bug Fixes

* trigger a release ([c8ce577](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/c8ce577999b09d79c235f15a5ecb5bd2accb774d))

# 1.0.0 (2023-11-30)


### Bug Fixes

* Add min and max values for INTEGER fields, to bound the values to Java Integer.MAX_VALUE ([46440d9](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/46440d94b3e58a63f4ec91928efcb0a020ab8e9f))
* Compatibility with thingworx 9 ([8bd5d10](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/8bd5d1019d8d8e55bc906d592a9d8ae8fada47bc))
* fix issue with the production build being invalid ([1580fc1](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/1580fc14dfd19035b5bd3f73c08a678bf2b52d27))
* handle between filters for datetime fields ([cf43fc3](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/cf43fc335e870f3f622a00d421de4687985a9875))
* Handle cases where the initial query is empty ([945df9f](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/945df9fe9065732ecc19e5fa45a2a99d84e10882))


### Features

* add "IN" and "NOTIN" operators ([#44](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/issues/44)) ([732bc50](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/732bc508e7350da87a91224bb76f74fef12ffe46))
* Add two new properties, `ContainsValidQuery` and `IsQueryEmpty` ([12f2ac0](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/12f2ac081e3dcb08d9973626ae47038301d79daa))
* updated dependencies, adopt latest template project ([43cf8ae](https://github.com/ptc-iot-sharing/QueryBuilderWidgetTWX/commit/43cf8ae9dd1da7649c86f88c5c8acf23ff15851e))
