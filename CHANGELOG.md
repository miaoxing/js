## [0.4.4](https://github.com/miaoxing/miaoxing-js/compare/v0.4.3...v0.4.4) (2022-08-02)





### Dependencies

* **@miaoxing/dev:** upgrade from `8.1.2` to `8.1.3`

## [0.4.3](https://github.com/miaoxing/miaoxing-js/compare/v0.4.2...v0.4.3) (2022-07-01)


### Features

* **experimental:** 增加 `$.fullUrl` 接口 ([d5f98ad](https://github.com/miaoxing/miaoxing-js/commit/d5f98ad2a190f520f56fbbac870d73e8cfe1c562))





### Dependencies

* **@miaoxing/dev:** upgrade from `8.1.1` to `8.1.2`

## [0.4.2](https://github.com/miaoxing/miaoxing-js/compare/v0.4.1...v0.4.2) (2022-06-01)





### Dependencies

* **@miaoxing/dev:** upgrade from `8.1.0` to `8.1.1`

## [0.4.1](https://github.com/miaoxing/miaoxing-js/compare/v0.4.0...v0.4.1) (2022-02-05)





### Dependencies

* **@miaoxing/dev:** upgrade from `8.0.1` to `8.1.0`

# [0.4.0](https://github.com/miaoxing/miaoxing-js/compare/v0.3.0...v0.4.0) (2022-01-12)


### Features

* 更新 typescript 到 `^4.5.2` ([a87e1b6](https://github.com/miaoxing/miaoxing-js/commit/a87e1b6fc3f00342cd2a144bf33e8fcaf91742cb))


### BREAKING CHANGES

* 更新 typescript 到 `^4.5.2`





### Dependencies

* **@miaoxing/dev:** upgrade from `8.0.0` to `8.0.1`

# [0.3.0](https://github.com/miaoxing/miaoxing-js/compare/v0.2.5...v0.3.0) (2021-10-28)


### Code Refactoring

* **$.http:** `$.http` 改为返回原始 `response` 对象，其中包含 `ret` 对象 ([9a53567](https://github.com/miaoxing/miaoxing-js/commit/9a5356761c5e774f3bb2cee86f9337f2aadc0ef8))


### Features

* **ret:** 增加 `Ret.isSuc` 和 `Ret.isErr` 方法，用于判断结果是否成功失败 ([5be6247](https://github.com/miaoxing/miaoxing-js/commit/5be62478eb20025e7de38d9b4e4442cced0e1c3a))
* **ret:** 增加 `Ret.suc` 和 `Ret.err` 方法用于快速创建 `Ret` 对象 ([cda4b5e](https://github.com/miaoxing/miaoxing-js/commit/cda4b5e43a3fc75d1eef13073fdabbad4c01a966))


### BREAKING CHANGES

* **$.http:** `$.http` 改为返回原始 `response` 对象，其中包含 `ret` 对象





### Dependencies

* **@miaoxing/dev:** upgrade from `7.0.1` to `8.0.0`

## [0.2.5](https://github.com/miaoxing/miaoxing-js/compare/v0.2.4...v0.2.5) (2021-05-12)





### Dependencies

* **@miaoxing/dev:** upgrade from `7.0.0` to `7.0.1`

## [0.2.4](https://github.com/miaoxing/miaoxing-js/compare/v0.2.3...v0.2.4) (2021-05-11)





### Dependencies

* **@miaoxing/dev:** upgrade from `6.4.0` to `7.0.0`

## [0.2.3](https://github.com/miaoxing/miaoxing-js/compare/v0.2.2...v0.2.3) (2021-04-27)





### Dependencies

* **@miaoxing/dev:** upgrade from `6.3.4` to `6.4.0`

## [0.2.2](https://github.com/miaoxing/miaoxing-js/compare/v0.2.1...v0.2.2) (2021-03-22)





### Dependencies

* **@miaoxing/dev:** upgrade from `6.3.3` to `6.3.4`

## [0.2.1](https://github.com/miaoxing/miaoxing-js/compare/v0.2.0...v0.2.1) (2021-03-12)





### Dependencies

* **@miaoxing/dev:** upgrade from `6.3.2` to `6.3.3`

# [0.2.0](https://github.com/miaoxing/miaoxing-js/compare/v0.1.10...v0.2.0) (2021-03-11)


### Bug Fixes

* `$.http` 改为返回 `Ret` 对象 ([54edf8c](https://github.com/miaoxing/miaoxing-js/commit/54edf8c299c93df342595b3e366975ac8fc85f3c))
* `$.ret` 允许传入 js 对象 ([618cedb](https://github.com/miaoxing/miaoxing-js/commit/618cedbeb1dcb3bbd77aeea649f19cc4162c662d))


### BREAKING CHANGES

* `$.http` 改为返回 `Ret` 对象

## [0.1.10](https://github.com/miaoxing/miaoxing-js/compare/v0.1.9...v0.1.10) (2021-03-10)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.3.1 to 6.3.2

## [0.1.9](https://github.com/miaoxing/miaoxing-js/compare/v0.1.8...v0.1.9) (2021-03-09)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.3.0 to 6.3.1

## [0.1.8](https://github.com/miaoxing/miaoxing-js/compare/v0.1.7...v0.1.8) (2021-03-09)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.2.0 to 6.3.0

## [0.1.7](https://github.com/miaoxing/miaoxing-js/compare/v0.1.6...v0.1.7) (2021-03-05)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.1.2 to 6.2.0

## [0.1.6](https://github.com/miaoxing/miaoxing-js/compare/v0.1.5...v0.1.6) (2021-03-05)


### Features

* **Ret:** 增加 `new` 静态方法，用于创建 `Ret` 类 ([c5d64f3](https://github.com/miaoxing/miaoxing-js/commit/c5d64f34c7cbc12a85ca831abd7884c70a928f44))
* 增加 `Ret` 类，http 相关接口改为返回 `Ret` 对象，兼容原生对象 ([14b6246](https://github.com/miaoxing/miaoxing-js/commit/14b62464c0b7e5f547f91b15a950f4df66326b19))

## [0.1.5](https://github.com/miaoxing/miaoxing-js/compare/v0.1.4...v0.1.5) (2020-09-25)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.1.1 to 6.1.2

## [0.1.4](https://github.com/miaoxing/miaoxing-js/compare/v0.1.3...v0.1.4) (2020-09-01)


### Features

* 增加 $.http $.patch $.put $.delete 接口 ([7f81bda](https://github.com/miaoxing/miaoxing-js/commit/7f81bdaee4415f04b7e716613f6e7abe4ba85de8))
* 增加 $.req $.url $.apiUrl 接口 ([1af7c4a](https://github.com/miaoxing/miaoxing-js/commit/1af7c4ad95c3c0ccb85770f5514dfbfcb63d3898))

## [0.1.3](https://github.com/miaoxing/miaoxing-js/compare/v0.1.2...v0.1.3) (2020-08-17)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.1.0 to 6.1.1

## [0.1.2](https://github.com/miaoxing/miaoxing-js/compare/v0.1.1...v0.1.2) (2020-08-14)





### Dependencies

* **@miaoxing/dev:** upgrade from 6.0.0 to 6.1.0

## [0.1.1](https://github.com/miaoxing/miaoxing-js/compare/v0.1.0...v0.1.1) (2020-08-14)





### Dependencies

* **@miaoxing/dev:** upgrade from  to 0.1.0

# 0.1.0 (2020-08-13)


### Features

* 首次发布 ([78f650b](https://github.com/miaoxing/miaoxing-js/commit/78f650b51e169a877164d5aa794a8d79c3d868f4))
