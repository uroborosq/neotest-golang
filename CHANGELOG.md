# Changelog

## [1.0.0](https://github.com/uroborosq/neotest-golang/compare/v0.2.0...v1.0.0) (2024-07-02)


### ⚠ BREAKING CHANGES

* rename arguments/options

### Features

* accept arguments, update readme ([ca46d64](https://github.com/uroborosq/neotest-golang/commit/ca46d648a3df8e4c86a3c16dc51a5f38cc7b95e1))
* add dap config, skip parsing test output for dap ([1e1cc1b](https://github.com/uroborosq/neotest-golang/commit/1e1cc1b317c91dbf8b91288510565c3abc6d6562))
* add json parsing ([4b196ec](https://github.com/uroborosq/neotest-golang/commit/4b196ecacafc8ec7c968d41782938fa663d3e676))
* add maintainer/dev notification for association issues ([ffba575](https://github.com/uroborosq/neotest-golang/commit/ffba575aaa0c54dd9f8a6c02a59948fb3e30053e))
* add pkgx config for go ([e12fd03](https://github.com/uroborosq/neotest-golang/commit/e12fd033c2cd5693b1999cd4f6a429490a9f0a3d))
* add screenshot ([a8eada4](https://github.com/uroborosq/neotest-golang/commit/a8eada461d4064bdb9779aaf45b8c87c56cf8877))
* add support for position type 'dir' ([8acce7e](https://github.com/uroborosq/neotest-golang/commit/8acce7e1dfbb900b39642d736039c226ed93fbf0))
* add test suite ([927f66c](https://github.com/uroborosq/neotest-golang/commit/927f66c5f0a902b5a14d4ae3d1a6a5b2544da342))
* ci linting/formatting/vuln ([2fe6f3a](https://github.com/uroborosq/neotest-golang/commit/2fe6f3aa410d8c06673fbac1a3a1976263fceda4))
* **ci:** add stale ([7d0c752](https://github.com/uroborosq/neotest-golang/commit/7d0c75265cbd4567f4a41795c263913c354c7a91))
* **ci:** run vuln checks on cron schedule ([0a6f062](https://github.com/uroborosq/neotest-golang/commit/0a6f062d1f3c5690d4c0ec05a6a325c604a1d9c0))
* compare against parens chars ([514cf7c](https://github.com/uroborosq/neotest-golang/commit/514cf7c22c9acc125e7881198fd8027642789301))
* detect suite, dir, file or test ([6338f18](https://github.com/uroborosq/neotest-golang/commit/6338f1881f1d81726165748b192cff6e3e85705e))
* gotestsum (for now) ([de03ee6](https://github.com/uroborosq/neotest-golang/commit/de03ee65e0669e93de60632359c63fd2c8d947e2))
* govulncheck ([2498842](https://github.com/uroborosq/neotest-golang/commit/2498842b3542daa4323836b392b173b922a90fd9))
* initial commit ([c9bb04e](https://github.com/uroborosq/neotest-golang/commit/c9bb04e720059e86bc0b27a7394d5d3c4de3bc20))
* initial testify suite support ([1513d9b](https://github.com/uroborosq/neotest-golang/commit/1513d9bb0f324cff9d2aae5e4b908cb791314d90))
* mark empty test files as skipped ([2a27fb9](https://github.com/uroborosq/neotest-golang/commit/2a27fb9f5a2023d77dcc3d82439d58c4475e3652))
* remove dependency on gotestsum ([e661e48](https://github.com/uroborosq/neotest-golang/commit/e661e4866bd804c539660ac02acaaa7d297565da))
* shorten down debugger config name ([bf96d5d](https://github.com/uroborosq/neotest-golang/commit/bf96d5d9e047e9d4e1418752c966f9924871b167))
* show one accumulated warning instead of individual ones ([269ca36](https://github.com/uroborosq/neotest-golang/commit/269ca36cb7979e8bb40b7fd09598e9d2c6af122f))
* simplify project root detection (better monorepo support) ([43b5690](https://github.com/uroborosq/neotest-golang/commit/43b56903239fb4d8518101731e0fc49512f54bf2))
* supply nvim-dap-go with cwd ([4b21fb8](https://github.com/uroborosq/neotest-golang/commit/4b21fb883442d3c21d4b245fa8a348c42d794231))
* support debugging of test ([2f20b7e](https://github.com/uroborosq/neotest-golang/commit/2f20b7e88885b909be33a7f4449759e074358ee2))
* support running tests in subprojects ([e839db0](https://github.com/uroborosq/neotest-golang/commit/e839db05839411319b07082148e23ac7a57a73d6))
* support table tests defined in for loop ([#71](https://github.com/uroborosq/neotest-golang/issues/71)) ([5d13357](https://github.com/uroborosq/neotest-golang/commit/5d1335746d8975f736ce3ca9a9eec72a1412c39d))
* use ${fileDirName} as program ([8a4c5ae](https://github.com/uroborosq/neotest-golang/commit/8a4c5aeb8647405c1d78ffd92bebbdc11cb46534))
* use Makefile ([5ce7d8e](https://github.com/uroborosq/neotest-golang/commit/5ce7d8e28f284335ecd0235210a0ce02487518e5))
* warn if test was not executed ([d7c005b](https://github.com/uroborosq/neotest-golang/commit/d7c005bef4be5f6bc485233fd3a78265ef4ca3ed))


### Bug Fixes

* allow brackets ([945f5a8](https://github.com/uroborosq/neotest-golang/commit/945f5a8ca3c5aa0a9f8275156849927373e88a12))
* allow single quotes ([52f7483](https://github.com/uroborosq/neotest-golang/commit/52f74839e747f3cac861a3f5aa09672487b77599))
* avoid crash when detecting a panic ([7a647e8](https://github.com/uroborosq/neotest-golang/commit/7a647e8a0eba19ae2e9f0a242c8c27bad01cfc0d))
* **ci:** move 'go vet' to linting ([bf07e9f](https://github.com/uroborosq/neotest-golang/commit/bf07e9ff7df6269d75f87dc6b4c1f0074bf3f9c0))
* do not accumulate tables ([b8d22db](https://github.com/uroborosq/neotest-golang/commit/b8d22db9c94e2c022926d0ce7b17a1324540dbeb))
* do not allow test skipping ([#72](https://github.com/uroborosq/neotest-golang/issues/72)) ([8973d54](https://github.com/uroborosq/neotest-golang/commit/8973d5449fbcfa32fd2b786cded748450b188844))
* do not include file/lineno in error ([5c0e222](https://github.com/uroborosq/neotest-golang/commit/5c0e222f4e9f93dd1e27533a95d7016ac8201bfd))
* do not show warning when no problems were found ([95bb7cb](https://github.com/uroborosq/neotest-golang/commit/95bb7cb8556e636c261b000df60e0ff37b0df1f1))
* escaping of []{} brackets were missing ([#64](https://github.com/uroborosq/neotest-golang/issues/64)) ([2dcc9e9](https://github.com/uroborosq/neotest-golang/commit/2dcc9e90d2d72b9d9ff41260b4dba1a319c369e6))
* git-diff make target ([0e4155a](https://github.com/uroborosq/neotest-golang/commit/0e4155a9c6bb514d0bb44107795b01c79c27e6f4))
* go test pattern did not escape parenthesis ([ad97cd3](https://github.com/uroborosq/neotest-golang/commit/ad97cd3095836f17c21b2aa99e7996d88f51b17b))
* mistake in Makefile ([2649202](https://github.com/uroborosq/neotest-golang/commit/264920296106a492cdfc708ad065b6c3fa7a9f65))
* off-by-one due to indexing ([93c81c6](https://github.com/uroborosq/neotest-golang/commit/93c81c6e7bccaee83a0843272abc51c4fd84d1a0))
* options not returned ([#63](https://github.com/uroborosq/neotest-golang/issues/63)) ([18c31a9](https://github.com/uroborosq/neotest-golang/commit/18c31a9373198a45397e2d6afa091390707c5e5c))
* regexp character escaping ([#70](https://github.com/uroborosq/neotest-golang/issues/70)) ([37f8877](https://github.com/uroborosq/neotest-golang/commit/37f887739ace41810dcd1a10cb2d650c5524831f))
* remove neodev config, use lazydev.nvim instead ([7c31823](https://github.com/uroborosq/neotest-golang/commit/7c318237b11f9a9f081f2141472d75b490b96dd2))
* remove prints ([dcff435](https://github.com/uroborosq/neotest-golang/commit/dcff43510ec0bc50140e45c2366cae2925e9dd63))
* remove timeout from default args ([#56](https://github.com/uroborosq/neotest-golang/issues/56)) ([b3821da](https://github.com/uroborosq/neotest-golang/commit/b3821daa8ca276bba9688740d5393f9f4d517642))
* remove todo ([76ab153](https://github.com/uroborosq/neotest-golang/commit/76ab153bbe0dca64e9d2a699e3f97c32e01f9e7e))
* remove unused ([1473c79](https://github.com/uroborosq/neotest-golang/commit/1473c794198764666b43ee1bd9a61e502c69b71a))
* rename arguments/options ([304df71](https://github.com/uroborosq/neotest-golang/commit/304df7126a1bbc63924d8898bf38b092fec25025))
* set cwd ([e4004e9](https://github.com/uroborosq/neotest-golang/commit/e4004e9bb1c71bda15c68ec32d7b4581365b163c))
* show right number of errors in diagnostics ([8a11fcb](https://github.com/uroborosq/neotest-golang/commit/8a11fcb822f9b1079420e6050a06ff73ef232ebe))
* typo ([e9c4ec5](https://github.com/uroborosq/neotest-golang/commit/e9c4ec5fd49ced25cb5b76243d022fd7435397c2))
* typo ([2fc213c](https://github.com/uroborosq/neotest-golang/commit/2fc213c18fa4e7c40f60fc310367893bb9e8f234))
* update screenshot ([5feaefb](https://github.com/uroborosq/neotest-golang/commit/5feaefb0b5ec2a30e2ac404038d958b0462abee3))
* use test's absolute folderpath as cwd ([2169e39](https://github.com/uroborosq/neotest-golang/commit/2169e392a6c4045cb1e59b1eb3bb5ef2aa09a22f))
* wrong link ([b477d01](https://github.com/uroborosq/neotest-golang/commit/b477d01290b252a74ccc55e047ce967e1e95a5d0))
* wrong tests path ([b3d1b01](https://github.com/uroborosq/neotest-golang/commit/b3d1b01e35c60db1e3fefeaa9e1980432970424e))

## [0.2.0](https://github.com/fredrikaverpil/neotest-golang/compare/v0.1.2...v0.2.0) (2024-06-29)


### Features

* support table tests defined in for loop ([#71](https://github.com/fredrikaverpil/neotest-golang/issues/71)) ([5d13357](https://github.com/fredrikaverpil/neotest-golang/commit/5d1335746d8975f736ce3ca9a9eec72a1412c39d))


### Bug Fixes

* do not allow test skipping ([#72](https://github.com/fredrikaverpil/neotest-golang/issues/72)) ([8973d54](https://github.com/fredrikaverpil/neotest-golang/commit/8973d5449fbcfa32fd2b786cded748450b188844))
* regexp character escaping ([#70](https://github.com/fredrikaverpil/neotest-golang/issues/70)) ([37f8877](https://github.com/fredrikaverpil/neotest-golang/commit/37f887739ace41810dcd1a10cb2d650c5524831f))

## [0.1.2](https://github.com/fredrikaverpil/neotest-golang/compare/v0.1.1...v0.1.2) (2024-06-28)


### Bug Fixes

* escaping of []{} brackets were missing ([#64](https://github.com/fredrikaverpil/neotest-golang/issues/64)) ([2dcc9e9](https://github.com/fredrikaverpil/neotest-golang/commit/2dcc9e90d2d72b9d9ff41260b4dba1a319c369e6))
* options not returned ([#63](https://github.com/fredrikaverpil/neotest-golang/issues/63)) ([18c31a9](https://github.com/fredrikaverpil/neotest-golang/commit/18c31a9373198a45397e2d6afa091390707c5e5c))

## [0.1.1](https://github.com/fredrikaverpil/neotest-golang/compare/v0.1.0...v0.1.1) (2024-06-25)


### Bug Fixes

* remove timeout from default args ([#56](https://github.com/fredrikaverpil/neotest-golang/issues/56)) ([b3821da](https://github.com/fredrikaverpil/neotest-golang/commit/b3821daa8ca276bba9688740d5393f9f4d517642))

## 0.1.0 (2024-06-24)

Initial release.
