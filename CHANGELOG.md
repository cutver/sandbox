# Changelog

All notable changes to this project will be documented in this file.

## v1.0.0 — 2026-11-12

> [!WARNING]
> **Breaking changes**
> - **api**: rename the payload field ([47827ef](https://github.com/cutver/sandbox/commit/47827ef8f46fb002e402c0dcc5ff4f2385300160)) by @Row0902
>   > **Migration**: the payload field moved to `notes`, so consumers must read it there.

### ✨ Features
- **api**: add the widget endpoint ([22507af](https://github.com/cutver/sandbox/commit/22507aff3bd28ec00a690502480fa89c6cec84b6)) by @Row0902

### 🧰 Maintenance
- **cli**: undo the flag rename ([8670951](https://github.com/cutver/sandbox/commit/867095197021a93367cc73b3c70a05da58f86805)) by @Row0902

### 🧰 Maintenance
- **parser**: cover the empty entry ([743b314](https://github.com/cutver/sandbox/commit/743b314a8e895b571a7f4e4b76734afe28aab4f7)) by @Row0902

### 🧰 Maintenance
- **cargo**: pin the toolchain ([65ba4bc](https://github.com/cutver/sandbox/commit/65ba4bc662507a940f827de1970d0f32e126d122)) by @Row0902

### 🧰 Maintenance
- **deps**: bump serde ([2834bc7](https://github.com/cutver/sandbox/commit/2834bc70bdf7f0aad92a309639a2e02ea076eed1)) by @Row0902

### 🔄 Refactoring
- **db**: split the query builder ([de68ffd](https://github.com/cutver/sandbox/commit/de68ffd65736c482c2914c6ae0daaefdd032cd8f)) by @Row0902

### ⚡ Performance
- **core**: cache the manifest parse ([140baf2](https://github.com/cutver/sandbox/commit/140baf29389f30649ea51c04ff7b9e0f7f6e70be)) by @Row0902

### 🐛 Fixes
- **cli**: stop dropping scoped commits ([2b576f7](https://github.com/cutver/sandbox/commit/2b576f7eb4caa6aafadf599d5f4854bd860d84f6)) by @Row0902

### 🧰 Maintenance
- **fmt**: normalise imports ([fd994d4](https://github.com/cutver/sandbox/commit/fd994d453cce3425e779239e880fbf04e48dc87f)) by @Row0902

### 📚 Documentation
- **readme**: explain the quick path ([79cc247](https://github.com/cutver/sandbox/commit/79cc2473aa6f5a31a0c7ca7e6bc6dce975c14da6)) by @Row0902

### 👥 Contributors
@Row0902

[Compare v0.2.6...v1.0.0](https://github.com/cutver/sandbox/compare/v0.2.6...v1.0.0)
## v0.2.6 — 2026-11-12
### 👥 Contributors
@Row0902

[Compare v0.2.5...v0.2.6](https://github.com/cutver/sandbox/compare/v0.2.5...v0.2.6)
## v0.2.5 — 2026-11-12
### 🧰 Maintenance
- **template**: adopt the redesigned release entry ([cbe2279](https://github.com/cutver/sandbox/commit/cbe22791475545bb12f03de1fca1095e412d58b6)) by @Row0902

### 👥 Contributors
@Row0902

[Compare v0.2.4...v0.2.5](https://github.com/cutver/sandbox/compare/v0.2.4...v0.2.5)
## [v0.2.4] - 2026-11-12
### 👥 Contributors
- @Row0902


---
**Full Changelog**: https://github.com/cutver/sandbox/compare/v0.2.3...v0.2.4 • *CI Build #13*
## [v0.2.3] - 2026-11-12
### 🛠️ Maintenance & Dependencies
- practice the draft-then-publish flow in the canary release ([31efbb7](https://github.com/cutver/sandbox/commit/31efbb74a0e1d15bfbb98b2c1238c9598d19d539)) by @agent

### 👥 Contributors
- @agent
- @cutver-release[bot]


---
**Full Changelog**: https://github.com/cutver/sandbox/compare/v0.2.2...v0.2.3 • *CI Build #12*
## [v0.2.2] - 2026-11-12
### 👥 Contributors
- @cutver-release[bot]


---
**Full Changelog**: https://github.com/cutver/sandbox/compare/v0.2.1...v0.2.2 • *CI Build #11*
## [v0.2.1] - 2026-11-11
### 🐛 Bug Fixes
- **cli**: optimize memory buffer allocation ([cf89900](https://github.com/cutver/sandbox/commit/cf8990024201f993edf2a2753b0d4ef1d8255c34)) by @Row0902

### 🛠️ Maintenance & Dependencies
- set default bump to auto and enforce check-changelog validation ([3f3f280](https://github.com/cutver/sandbox/commit/3f3f280e699593ebf1270f3b303e58084ff5c7b6)) by @Row0902

### 👥 Contributors
- @Row0902
- @cutver-release[bot]


---
**Full Changelog**: https://github.com/cutver/sandbox/compare/v0.2.0...v0.2.1 • *CI Build #10*
## [v0.2.0] - 2026-11-11
### 🐛 Bug Fixes
- **parser**: correct edge case when parsing empty input ([08d99b8](https://github.com/cutver/sandbox/commit/08d99b841d5c6f1519cdb684da4e4ce7deb0cdb1)) by @Row0902

### 🚀 Features & Enhancements
- **calculator**: add high performance calculation engine ([7cb0613](https://github.com/cutver/sandbox/commit/7cb06139cbc3a5ceff7c64aa704840ee7872dff4)) by @Row0902

### 🛠️ Maintenance & Dependencies
- configure MiniJinja release template in cutver.toml and workflow ([44d3caa](https://github.com/cutver/sandbox/commit/44d3caae025fe28ca18c5f2a99bff2b6bc778e6f)) by @Row0902

### 👥 Contributors
- @Row0902
- @cutver-release[bot]


---
**Full Changelog**: https://github.com/cutver/sandbox/compare/v0.1.2...v0.2.0 • *CI Build #8*
## [v0.1.2] - 2026-11-11

### Maintenance
- push commit from workflow to avoid tag collision with github-publish
## [v0.1.1] - 2026-11-11

### Features
- initialize cutver sandbox testbed with github-publish plugin

### Bug Fixes
- pass GITHUB_REPOSITORY to plugin permissions env
- configure manifest in cutver.toml and fetch plugin in release workflow

### Maintenance
- bump plugin to v0.1.2 and enable publish push
- bump github-publish plugin to v0.1.1
- authenticate release workflow using cutver-release bot token
## [0.1.0] - 2026-11-11

### Added
- Initial canary sandbox release
