## [0.2.2](https://github.com/zakodium/adonis-mongodb/compare/v0.2.1...v0.2.2) (2020-09-09)


### Bug Fixes

* correct incremental id in AutoIncrementModel ([8a20201](https://github.com/zakodium/adonis-mongodb/commit/8a20201c1d86618c2f068304c2b109b5a86a33d6))
* do not create a config subfolder ([#4](https://github.com/zakodium/adonis-mongodb/issues/4)) ([a86e79b](https://github.com/zakodium/adonis-mongodb/commit/a86e79b4df34b97084e23204423d012e393432d0))
* show accurate information in status command ([6580db9](https://github.com/zakodium/adonis-mongodb/commit/6580db92bfa7a4c752cf39c2c084ad2d8b67b500))



## [0.2.1](https://github.com/zakodium/adonis-mongodb/compare/v0.2.0...v0.2.1) (2020-09-02)



# [0.2.0](https://github.com/zakodium/adonis-mongodb/compare/v0.1.7...v0.2.0) (2020-09-02)


### Bug Fixes

* correct migration batch number ([66af888](https://github.com/zakodium/adonis-mongodb/commit/66af8882011ec0b14e7567d66231ab14f4b7f50e))
* don't log description twice ([923048f](https://github.com/zakodium/adonis-mongodb/commit/923048f0963d1dc5f80c1dc9cca7760331a6bcea))
* only use transaction when creating indexes if collection does not exist ([94fa3fb](https://github.com/zakodium/adonis-mongodb/commit/94fa3fb7b69cf079f372f51813a5dbaf08b0bde0))
* use original type on id getter ([78317c1](https://github.com/zakodium/adonis-mongodb/commit/78317c12ea25c624e85b7deb094966c1e2f852c7))


### Features

* add command show migration status ([0ef66d2](https://github.com/zakodium/adonis-mongodb/commit/0ef66d2a31e5c9782f80383dd48ec72276b4eac1))
* add defer method to migration module ([ff7c60a](https://github.com/zakodium/adonis-mongodb/commit/ff7c60a89d0c92cedaba4c4e918fcfab6ee3e0a6))
* add incremental model ([e7574f6](https://github.com/zakodium/adonis-mongodb/commit/e7574f6bcd2b3840f1cd3c8f6d195d3ccd781e64))
* allow to add description to migration ([7c075e7](https://github.com/zakodium/adonis-mongodb/commit/7c075e77dde28a2c3337b27e7abbc7833a6af793))
* execute all pending migrations in one transaction ([1581854](https://github.com/zakodium/adonis-mongodb/commit/1581854a4b95dd285d6f3ac86002cf293511b2da))


* rename migrate command ([c6ce51b](https://github.com/zakodium/adonis-mongodb/commit/c6ce51bb281b408d3a6afde4ae2245ad96f6c5b9))


### BREAKING CHANGES

* do not convert to string in id getter
* Model is no longer a default export but a named export
* renamed the migrate command to match how lucid names migration commands



## [0.1.7](https://github.com/zakodium/adonis-mongodb/compare/v0.1.6...v0.1.7) (2020-04-14)



## [0.1.6](https://github.com/zakodium/adonis-mongodb/compare/v0.1.5...v0.1.6) (2020-01-13)


### Bug Fixes

* skip lib checks ([7fd8507](https://github.com/zakodium/adonis-mongodb/commit/7fd8507c85c45c2c2bdbe1e6ac9be5b0114dc233))
* **commands:** inject db in handle method ([303fdf1](https://github.com/zakodium/adonis-mongodb/commit/303fdf17b6381050859380ba473ebfab49903528))



## [0.1.5](https://github.com/zakodium/adonis-mongodb/compare/v0.1.4...v0.1.5) (2019-12-06)


### Bug Fixes

* actually execute the up() method ([3d8740f](https://github.com/zakodium/adonis-mongodb/commit/3d8740f4c380086818c5fe888d2bbeb1f01d4e8a))



## [0.1.4](https://github.com/zakodium/adonis-mongodb/compare/v0.1.3...v0.1.4) (2019-12-03)


### Bug Fixes

* enable emitDecoratorMetadata ([407554e](https://github.com/zakodium/adonis-mongodb/commit/407554e579197b52f16621ddd062668840407f07))



## [0.1.3](https://github.com/zakodium/adonis-mongodb/compare/v0.1.2...v0.1.3) (2019-12-03)


### Bug Fixes

* transpile optional properties ([d22d8d1](https://github.com/zakodium/adonis-mongodb/commit/d22d8d15981a33eb9c0928574e7f0c36e18a9c6b))



## [0.1.2](https://github.com/zakodium/adonis-mongodb/compare/v0.1.1...v0.1.2) (2019-12-03)


### Bug Fixes

* really correctly read templates ([ad4c812](https://github.com/zakodium/adonis-mongodb/commit/ad4c81217b8b51196aa8da72f11f35e7a0d02f02))



## [0.1.1](https://github.com/zakodium/adonis-mongodb/compare/v0.1.0...v0.1.1) (2019-12-03)


### Bug Fixes

* correctly refer to template directory ([dab86ad](https://github.com/zakodium/adonis-mongodb/commit/dab86ad199d5a7c9b9dc825035dad2875410b0d7))



# 0.1.0 (2019-12-03)


### Bug Fixes

* rename types from .d.ts to .ts ([4a0cd71](https://github.com/zakodium/adonis-mongodb/commit/4a0cd7179e52fb49c28a49e9ac8781afc0f7335e))


### Features

* initial library ([6c917cf](https://github.com/zakodium/adonis-mongodb/commit/6c917cf8bb76c01ba02ed90036c293f0667f6d81))



