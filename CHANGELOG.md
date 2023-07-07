# [3.5.0](https://github.com/ziccardi/jnrpe/compare/3.4.0...3.5.0) (2023-07-07)


### Bug Fixes

* fix the listening address for the Netty Network Provider ([7675f60](https://github.com/ziccardi/jnrpe/commit/7675f60eaca82d2e658b8d316242c1b144946e97))
* fixes a bug in checking the listening address. Now 0.0.0.0 is correctly evaluated ([0457e49](https://github.com/ziccardi/jnrpe/commit/0457e49f9f4b89c1473da5ac0ac7eae4a972f76b))


### Features

* adds ability to generate a sample skeleton configuration ([b396547](https://github.com/ziccardi/jnrpe/commit/b3965478f9df2a058db37859e7f94fd6eda9bd76))
* adds ability to run the configured commands ([71fb6fa](https://github.com/ziccardi/jnrpe/commit/71fb6fa137371fbeff83af65e4cd0f22029f04da)), closes [#57](https://github.com/ziccardi/jnrpe/issues/57)



# [3.4.0](https://github.com/ziccardi/jnrpe/compare/3.3.0...3.4.0) (2022-02-27)


### Features

* **network:** added SSL support to the TCP listener ([8d241b9](https://github.com/ziccardi/jnrpe/commit/8d241b9802aa2e49e486e7b16a628e991b4eb7d9)), closes [#115](https://github.com/ziccardi/jnrpe/issues/115)



# [3.3.0](https://github.com/ziccardi/jnrpe/compare/3.2.1...3.3.0) (2022-02-27)


### Bug Fixes

* added gradle.properties to resolve issue with Java 16+ ([102027a](https://github.com/ziccardi/jnrpe/commit/102027a3e6aa5ec5bbf32230ab0717d9bbf2af67))
* update picocli ([40f3621](https://github.com/ziccardi/jnrpe/commit/40f3621d3b9b2d8b20e21dc19cd2ae1c02ad5490))


### Features

* added simple token authentication and IP filtering ([efce8d4](https://github.com/ziccardi/jnrpe/commit/efce8d4f70da739ff01e6a8684e398c91bf4d639))



## [3.2.1](https://github.com/ziccardi/jnrpe/compare/3.2.0...3.2.1) (2022-02-16)


### Bug Fixes

* fixed build script ([4e48310](https://github.com/ziccardi/jnrpe/commit/4e483107b6ea9466071924dfb2fdd93622836631))



# [3.2.0](https://github.com/ziccardi/jnrpe/compare/3.1.1...3.2.0) (2020-12-22)


### Bug Fixes

* 🐛 added description for the start command ([7d70356](https://github.com/ziccardi/jnrpe/commit/7d703562da6d52fd19a77bea5370ec3c236859a9))


### Features

* **cli:** added commands to list plugins and get plugin help ([6e2097c](https://github.com/ziccardi/jnrpe/commit/6e2097ce56abcbb1fb0fbed0668462089fe5b015)), closes [#56](https://github.com/ziccardi/jnrpe/issues/56)
* **plugins:** implemented plugin execution ([a067981](https://github.com/ziccardi/jnrpe/commit/a067981a50f014c6141b58705336bd19be561414))
* **threshold:** implemented threshold syntax parsing and validation ([2932f80](https://github.com/ziccardi/jnrpe/commit/2932f808c00132e48ccf31fe7edfa5924fca94ce)), closes [#87](https://github.com/ziccardi/jnrpe/issues/87)



