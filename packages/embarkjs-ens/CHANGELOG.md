# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [4.2.0](https://github.com/embark-framework/embark/compare/v4.1.1...v4.2.0) (2019-12-18)


### Build System

* **deps:** bump web3[-*] from 1.2.1 to 1.2.4 ([e7ed552](https://github.com/embark-framework/embark/commit/e7ed552))


### BREAKING CHANGES

* **deps:** bump embark's minimum supported version of geth from
`>=1.8.14` to `>=1.9.0` and its minimum supported version of parity from
`>=2.0.0` to `>=2.2.1`. This is necessary since web3 1.2.4 makes use of the
`eth_chainId` RPC method (EIP 695) and those client versions are the earliest
ones to implement it.





## [4.1.1](https://github.com/embark-framework/embark/compare/v4.1.0...v4.1.1) (2019-08-28)

**Note:** Version bump only for package embarkjs-ens





# [4.1.0](https://github.com/embark-framework/embark/compare/v4.1.0-beta.6...v4.1.0) (2019-08-12)

**Note:** Version bump only for package embarkjs-ens





# [4.1.0-beta.6](https://github.com/embark-framework/embark/compare/v4.1.0-beta.5...v4.1.0-beta.6) (2019-08-09)

**Note:** Version bump only for package embarkjs-ens





# [4.1.0-beta.5](https://github.com/embark-framework/embark/compare/v4.1.0-beta.4...v4.1.0-beta.5) (2019-07-10)

**Note:** Version bump only for package embarkjs-ens





# [4.1.0-beta.4](https://github.com/embark-framework/embark/compare/v4.1.0-beta.3...v4.1.0-beta.4) (2019-06-27)


### Bug Fixes

* alleviate races re: embarkjs by introducing Plugin#addGeneratedCode and related refactors ([fc4faa8](https://github.com/embark-framework/embark/commit/fc4faa8))





# [4.1.0-beta.3](https://github.com/embark-framework/embark/compare/v4.1.0-beta.2...v4.1.0-beta.3) (2019-06-07)

**Note:** Version bump only for package embarkjs-ens