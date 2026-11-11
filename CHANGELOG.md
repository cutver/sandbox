# Changelog

All notable changes to this project will be documented in this file.

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
