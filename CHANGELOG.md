# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.0.0-rc.1"></a>
# [1.0.0-rc.1](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.9...v1.0.0-rc.1) (2018-06-21)


### Bug Fixes

* **account-send:** show amount validation errors on change ([b8cdf44](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b8cdf44))
* **app:** remove modal-header class from non-modal components ([a586f33](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a586f33))
* **electron:** grab arch correctly during build ([660132c](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/660132c))
* **electron:** specify secureProtocol for proxy and server ([7f57693](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/7f57693))
* **electron:** use node configuration version to determine if outdated ([9ab7ba5](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9ab7ba5))
* **status-tooltip:** better syncing check algorithm ([7c2c072](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/7c2c072))


### Features

* **electron:** support multi-arch builds (theoretically) ([a99c0f8](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a99c0f8))
* **electron:** update progress while verifying assets ([bbbec69](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/bbbec69))
* **legal:** add legal click-throughs ([ab92c6c](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ab92c6c))
* **start:** show loading animation while node is starting ([e5fa75d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/e5fa75d))



<a name="1.0.0-beta.9"></a>
# [1.0.0-beta.9](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.8...v1.0.0-beta.9) (2018-06-06)


### Bug Fixes

* **account-carousel:** cannot use [@guid](https://github.com/guid) key in Ember 3.2 ([fc2195d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/fc2195d))
* **account-send:** allow using new nano_ prefix ([a59b414](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a59b414))
* **app:** stop using flex layout for main element ([25970c6](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/25970c6))
* **generate-seed:** use 256-bit entropy when generating mnemonic ([b3b7cfe](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b3b7cfe))
* **mirage:** passthrough translation sideloading ([99f53fd](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/99f53fd))
* **notification-center:** make notifications are visible in small widths ([d5f0710](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/d5f0710))
* **rpc:** forgot to add generateId utility ([27d03f7](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/27d03f7))


### Features

* **account-settings:** allow changing account representative ([bf3601a](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/bf3601a))
* **app:** add new loading animations by exyoris ([a4ea611](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a4ea611))
* **app:** begin using new loading animations ([7ee7e53](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/7ee7e53))
* **intl:** add Bulgarian (bg-bg) translation by exyoris ([aa7753d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/aa7753d))
* **intl:** sideload translations ([80403fd](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/80403fd))
* **status-tooltip:** visually distinguish when syncing ([9f5b279](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9f5b279))


### Performance Improvements

* **send-button:** dramatically improve transition animation jank ([07eeef1](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/07eeef1))



<a name="1.0.0-beta.8"></a>
# [1.0.0-beta.8](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.7...v1.0.0-beta.8) (2018-05-28)


### Bug Fixes

* **app:** disable overflow on app window ([725fa24](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/725fa24))
* **download-progress:** show correct status when updating ([bea00db](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/bea00db))
* **intl:** fix invalid YAML ([ebe5bb3](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ebe5bb3))
* **intl:** normalize old locale variants ([2b349f2](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/2b349f2))
* **wallet-import:** save wallet seed during import ([f6f4b95](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f6f4b95))



<a name="1.0.0-beta.7"></a>
# [1.0.0-beta.7](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.6...v1.0.0-beta.7) (2018-04-11)


### Bug Fixes

* **status-tooltip:** don't start polling until component in viewport ([d274a54](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/d274a54))


### Features

* **account-send:** add send max button ([18facbe](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/18facbe))
* **app:** fade in main content on launch ([6139053](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/6139053))
* **balance-overview:** add EUR to convertable currencies ([72116f3](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/72116f3))
* **balance-overview:** routable currency conversion ([05c4fea](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/05c4fea))
* **format-amount:** allow disabling decimal separators ([c0bcff5](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/c0bcff5))
* **password-toggle:** allow configurable readonly ([49fe4c6](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/49fe4c6))
* **settings:** add ability to label accounts ([f8fd082](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f8fd082))
* **wallet-overview:** routable current account ([f313d10](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f313d10))
* **wallet-settings:** save seed during setup and display in settings ([b817737](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b817737))


### Performance Improvements

* **wallets:** use a modal for wallet settings and smooth transitions ([39cad40](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/39cad40))



<a name="1.0.0-beta.6"></a>
# [1.0.0-beta.6](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.5...v1.0.0-beta.6) (2018-03-20)


### Bug Fixes

* **account-address:** stop cutting out first character in the middle ([f6881e8](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f6881e8)), closes [#8](https://github.com/nano-wallet-company/nano-wallet-desktop/issues/8)
* **account-carousel:** properly show account card states as they load ([fc9083b](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/fc9083b)), closes [#12](https://github.com/nano-wallet-company/nano-wallet-desktop/issues/12)
* **electron:** wait for node to become available before ready ([c129b9e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/c129b9e)), closes [#10](https://github.com/nano-wallet-company/nano-wallet-desktop/issues/10)
* **format-amount:** integer component must be at least 1 digit ([f384a2b](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f384a2b)), closes [#7](https://github.com/nano-wallet-company/nano-wallet-desktop/issues/7)
* **history:** fix history element spacing ([431a725](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/431a725))
* **navbar-toggle:** fix mobile navbar toggle ([e8ae93a](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/e8ae93a))
* **wallet-overview:** add media queries for small heights ([ad9e321](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ad9e321))


### Features

* **account-card:** add notification when account address copied ([ae90ba2](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ae90ba2)), closes [#9](https://github.com/nano-wallet-company/nano-wallet-desktop/issues/9)
* **account-card:** copy account address when clicked ([d32cf48](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/d32cf48))
* **wallet-settings:** truncate representative address ([e17ff4f](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/e17ff4f))



<a name="1.0.0-beta.5"></a>
# [1.0.0-beta.5](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.4...v1.0.0-beta.5) (2018-03-14)


### Bug Fixes

* **account-history:** adjust history styling to mirror design ([8426a37](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/8426a37))
* **format-amount:** fix import of currency formats ([2f2ee7e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/2f2ee7e))
* **package:** remove previous artificial version bump ([510503b](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/510503b))
* **setup:** add new translations ([19513e8](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/19513e8))
* **setup:** save wallet after setup route ([79de33f](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/79de33f))
* **wallet-overview:** fix typos and fine tunning ([81fe390](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/81fe390))


### Features

* **navigation-bar:** add markup and style for navigation bar ([9101f74](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9101f74))
* **navigation-bar:** add markup and style for navigation bar ([dabe50b](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/dabe50b))
* **setup:** style setup and login flow ([9c98459](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9c98459))
* **wallet-settings:** add confirm password and ability to change rep ([aeccf4d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/aeccf4d))


### Performance Improvements

* **setup:** optimize setup backdrop ([f6c809e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f6c809e))
* **setup:** speed up setup transitions ([336664e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/336664e))



<a name="1.0.0-beta.4"></a>
# [1.0.0-beta.4](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.3...v1.0.0-beta.4) (2018-02-21)


### Bug Fixes

* **download-progress:** add error handler ([dabac8c](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/dabac8c))
* **electron:** ensure Windows targets use rai_node.exe ([8362414](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/8362414))
* **setup:** fix race conditions around setup and imports of wallets ([f4c6bb5](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f4c6bb5))



<a name="1.0.0-beta.3"></a>
# [1.0.0-beta.3](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2018-02-20)


### Bug Fixes

* **setup:** disable closing modals when backdrop clicked ([63477ad](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/63477ad))


### Features

* **electron:** add a default context menu ([57ab125](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/57ab125))
* **electron:** give UI feedback when verifying and extracting assets ([a0b6d3e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a0b6d3e))
* **electron:** log more pertinent information during asset downloads ([8edc25d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/8edc25d))
* **electron:** pick random ports for node when the defaults aretaken ([b18bfc0](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b18bfc0))
* **intl:** use custom currency formatting to support NANO ([4bbe402](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/4bbe402))



<a name="1.0.0-beta.2"></a>
# [1.0.0-beta.2](https://github.com/nano-wallet-company/nano-wallet-desktop/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2018-02-19)



<a name="1.0.0-beta.1"></a>
# 1.0.0-beta.1 (2018-02-19)


### Bug Fixes

* Fix bignum helper ([ad22057](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ad22057))
* **electron:** don't use a mixin to start the node ([28df0b6](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/28df0b6))
* **electron:** start node when routes require it ([0cc3a1a](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/0cc3a1a))
* **send:** Fix changing send source ([90ae764](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/90ae764))
* **status:** Fix status translations ([a605d99](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/a605d99))


### Features

* Add app manifest ([9c87c73](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9c87c73))
* Add basic adapters, serialization and services ([fa5e34b](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/fa5e34b))
* Add basic data layer ([b7661c5](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b7661c5))
* Add basic routes ([d980a4e](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/d980a4e))
* **wallet:** Always restore wallet to storage when entering route ([198d891](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/198d891))
* Add Bootstrap 4 ([313b854](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/313b854))
* **account:** Add account deletion functionality (but disable for now) ([bbd8230](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/bbd8230))
* **electron:** add node proxy server ([ed3ad46](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/ed3ad46))
* **electron:** begin accepting RPC callbacks in our proxy ([eb16d65](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/eb16d65))
* **electron:** Electron service ([755deca](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/755deca))
* **history:** Add history routes ([f980907](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f980907))
* **history:** Add row-level coloring to history ([0a04b76](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/0a04b76))
* **intl:** Add es-pr translation ([c628b48](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/c628b48))
* **overview:** Flesh out overview and send functionality ([378c7d1](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/378c7d1))
* **send:** Add send route ([f6c6f24](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/f6c6f24))
* **send:** More idiomatic send amounts ([7bca81d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/7bca81d))
* **setup:** Download rai_node from endpoint ([caaafe5](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/caaafe5))
* **setup:** Full wallet setup with mnemonic backup ([bf3e714](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/bf3e714))
* Auto convert between units ([fa806fe](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/fa806fe))
* **setup:** Implement asset downloader ([8f7ea66](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/8f7ea66))
* **setup:** Start setup routes ([98eec9d](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/98eec9d))
* **status:** Add status service ([89f6714](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/89f6714))
* **status-tooltip:** Add status-tooltip component ([b0ca80a](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/b0ca80a))
* **wallet:** Add wallet authentication using ember-simple-auth ([89edf29](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/89edf29))
* **wallet:** Persist wallet information ([c774075](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/c774075))
* **wallet:** poll for account balance changes within a wallet ([58e3f34](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/58e3f34))
* Add corber ([901fed1](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/901fed1))
* Add ember-cli-mirage ([1dfbfab](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/1dfbfab))
* Add ember-electron addon ([0a6d173](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/0a6d173))
* Add ember-intl ([769e3e1](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/769e3e1))
* Add ember-light-table ([1697fa8](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/1697fa8))
* Add new conversion utils ([9c87679](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/9c87679))
* **wallet:** require wallet authentication ([cbc7533](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/cbc7533))
* Add pagination ([26648e8](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/26648e8))
* **wallet:** Use wallet adapter to change seed ([67b84b7](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/67b84b7))
* Add service worker ([2ec94c0](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/2ec94c0))
* Full intl support ([6a03a01](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/6a03a01))
* Use ember-cli-content-for-config ([683d9a0](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/683d9a0))


### Performance Improvements

* **ajax:** Add ember-concurrency aware AJAX requests ([af9dbcd](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/af9dbcd))
* **ajax:** Change number of retries ([1fd85d6](https://github.com/nano-wallet-company/nano-wallet-desktop/commit/1fd85d6))
