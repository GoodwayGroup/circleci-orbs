# [2.1.0](https://github.com/GoodwayGroup/circleci-orb/compare/v2.0.2...v2.1.0) (2022-02-17)


### Features

* **ecr:** SMS-440 added executor and jobs to manage ecr hosted docker images. ([#40](https://github.com/GoodwayGroup/circleci-orb/issues/40)) ([55d6dbf](https://github.com/GoodwayGroup/circleci-orb/commit/55d6dbfb0c7038654c43910a8a337bfd1107df89))

## [2.0.2](https://github.com/GoodwayGroup/circleci-orb/compare/v2.0.1...v2.0.2) (2021-05-18)

## [2.0.1](https://github.com/GoodwayGroup/circleci-orb/compare/v2.0.0...v2.0.1) (2021-05-18)

# [2.0.0](https://github.com/GoodwayGroup/circleci-orb/compare/v1.3.3...v2.0.0) (2021-02-18)


### Features

* **node lint:** add npm run lint step to the test-nodejs task ([#13](https://github.com/GoodwayGroup/circleci-orb/issues/13)) ([1fbc03f](https://github.com/GoodwayGroup/circleci-orb/commit/1fbc03f4f12960f7e4c15a4b7416006702d998f3))


### BREAKING CHANGES

* **node lint:** job `test-nodejs` now enables linting by default via the command `npm run lint`

## [1.3.3](https://github.com/GoodwayGroup/circleci-orb/compare/v1.3.2...v1.3.3) (2021-01-20)


### Bug Fixes

* **determine-docker-tag:** remove @ from tag and branch name ([#12](https://github.com/GoodwayGroup/circleci-orb/issues/12)) ([2a5baa6](https://github.com/GoodwayGroup/circleci-orb/commit/2a5baa6716cc0bd1af98136c30b8898870dbda26))

## [1.3.2](https://github.com/GoodwayGroup/circleci-orb/compare/v1.3.1...v1.3.2) (2021-01-12)


### Bug Fixes

* **deploy-dag:** correct slack notification and project folder copy into nested folder ([#11](https://github.com/GoodwayGroup/circleci-orb/issues/11)) ([cbcada8](https://github.com/GoodwayGroup/circleci-orb/commit/cbcada8757d5b2c33b2ee09e7d95b80b878d1ac1))

## [1.3.1](https://github.com/GoodwayGroup/circleci-orb/compare/v1.3.0...v1.3.1) (2020-12-22)


### Bug Fixes

* **test-python:** corrected cached paths ([e7b15a0](https://github.com/GoodwayGroup/circleci-orb/commit/e7b15a09d063e3ec6a7f59245246954fcc89b574))

# [1.3.0](https://github.com/GoodwayGroup/circleci-orb/compare/v1.2.0...v1.3.0) (2020-12-01)


### Features

* **python:** added dag deploy and python test jobs ([#7](https://github.com/GoodwayGroup/circleci-orb/issues/7)) ([7700b4c](https://github.com/GoodwayGroup/circleci-orb/commit/7700b4c281f6fe2f074cb3a7020308b7016e0ba5))

# [1.2.0](https://github.com/GoodwayGroup/circleci-orb/compare/v1.1.0...v1.2.0) (2020-07-27)


### Bug Fixes

* **deploy:** removed requirement on notification-channel ([7310297](https://github.com/GoodwayGroup/circleci-orb/commit/731029783ed519b6ff5f3ff86a5cfeea3e583f71)), closes [#4](https://github.com/GoodwayGroup/circleci-orb/issues/4)


### Features

* add post-steps to deployment job ([d58278e](https://github.com/GoodwayGroup/circleci-orb/commit/d58278e66b7302946866aa074600504dbe63ec9b))
* added notify rollbar command ([d49851e](https://github.com/GoodwayGroup/circleci-orb/commit/d49851eaf16feb97d3d6b1ef450000884a57a4b1))

# [1.1.0](https://github.com/GoodwayGroup/circleci-orb/compare/v1.0.1...v1.1.0) (2020-07-27)


### Features

* added executor and jobs ([01ec4e2](https://github.com/GoodwayGroup/circleci-orb/commit/01ec4e214db86789da5477f08f9b0d8a5290c23f))

## [1.0.1](https://github.com/GoodwayGroup/circleci-orb/compare/v1.0.0...v1.0.1) (2020-06-30)


### Bug Fixes

* typo in orb name in releaserc ([c92e6a9](https://github.com/GoodwayGroup/circleci-orb/commit/c92e6a9d94d1ecec2dc89cfe2fd2af87c08f1daf))

# 1.0.0 (2020-06-27)


### Bug Fixes

* releaserc circleci path ([666c7d6](https://github.com/GoodwayGroup/circleci-orb/commit/666c7d682b80a45f95783328cec905480030e754))


### Features

* initial commit ([689c2d6](https://github.com/GoodwayGroup/circleci-orb/commit/689c2d6b0ff85f38eaa7bd0feafa7259528182fa))
