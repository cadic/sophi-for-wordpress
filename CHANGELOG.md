# Changelog

All notable changes to this project will be documented in this file, per [the Keep a Changelog standard](http://keepachangelog.com/), and will adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] - TBD

## [1.0.13] - 2022-04-20
### Changed
- `keywords` data type from string to array (props [@iamdharmesh](https://github.com/iamdharmesh), [@jeffpaul](https://github.com/jeffpaul), [@oscarssanchez](https://github.com/oscarssanchez), [@YMufleh](https://github.com/YMufleh) via [#233](https://github.com/globeandmail/sophi-for-wordpress/pull/233)).

### Security
- Bump `node-forge` from 1.2.1 to 1.3.0 (props [@dependabot](https://github.com/apps/dependabot) via [#228](https://github.com/globeandmail/sophi-for-wordpress/pull/228)).
- Bump `minimist` from 1.2.5 to 1.2.6 (props [@dependabot](https://github.com/apps/dependabot) via [#229](https://github.com/globeandmail/sophi-for-wordpress/pull/229)).
- Update dependency `10up-toolkit` from 3.0.3 to 3.1.2 (props [@renovate](https://github.com/apps/renovate) via [#230](https://github.com/globeandmail/sophi-for-wordpress/pull/230), [#234](https://github.com/globeandmail/sophi-for-wordpress/pull/234)).
- Update dependency `phpunit/phpunit` from 8.5.25 to 8.5.26 (props [@renovate](https://github.com/apps/renovate) via [#231](https://github.com/globeandmail/sophi-for-wordpress/pull/231)).
- Bump `async` from 2.6.3 to 2.6.4 (props [@dependabot](https://github.com/apps/dependabot) via [#235](https://github.com/globeandmail/sophi-for-wordpress/pull/235)).

## [1.0.12] - 2022-03-23
### Fixed
- PHP fatal error when duplicating posts across sites (props [@YMufleh](https://github.com/YMufleh) via [#218](https://github.com/globeandmail/sophi-for-wordpress/pull/218)).

### Security
- Update dependency `phpunit/phpunit` from 8.5.23 to 8.5.25 (props [@renovate](https://github.com/apps/renovate) via [#214](https://github.com/globeandmail/sophi-for-wordpress/pull/214), [#220](https://github.com/globeandmail/sophi-for-wordpress/pull/220)).
- Update dependency `10up-toolkit` from 3.0.2 to 3.0.3 (props [@renovate](https://github.com/apps/renovate) via [#217](https://github.com/globeandmail/sophi-for-wordpress/pull/217)).

## [1.0.11] - 2022-03-03
### Changed
- Update `package-lock.json` (props [@jeffpaul](https://github.com/jeffpaul) via [#197](https://github.com/globeandmail/sophi-for-wordpress/pull/197)).

### Security
- Update `actions/setup-node` action from v2 to v3 (props [@renovate](https://github.com/apps/renovate) via [#199](https://github.com/globeandmail/sophi-for-wordpress/pull/199)).
- Update `actions/checkout` action from v2 to v3 (props [@renovate](https://github.com/apps/renovate) via [#202](https://github.com/globeandmail/sophi-for-wordpress/pull/202)).
- Update dependency `10up-toolkit` from 2.1.1 to 3.0.2 (props [@renovate](https://github.com/apps/renovate) via [#203](https://github.com/globeandmail/sophi-for-wordpress/pull/203), [#210](https://github.com/globeandmail/sophi-for-wordpress/pull/210)).

## [1.0.10] - 2022-02-28
### Changed
- Sets the default timeout of the first Sophi request and the cron request to 3 seconds (props [@oscarssanchez](https://github.com/oscarssanchez), [@barryceelen](https://github.com/barryceelen), [@felipeelia](https://github.com/felipeelia), [@tott](https://github.com/tott) via [#198](https://github.com/globeandmail/sophi-for-wordpress/pull/198)).

### Security
- Update dependency `snowplow/snowplow-tracker` from 0.4.0 to 0.5.0 (props [@renovate](https://github.com/apps/renovate) via [#186](https://github.com/globeandmail/sophi-for-wordpress/pull/186)).

## [1.0.9] - 2022-02-18
### Added
- `hostname` and `path` fields to schema (props [@Rahmon](https://github.com/Rahmon), [@dinhtungdu](https://github.com/dinhtungdu) via [#164](https://github.com/globeandmail/sophi-for-wordpress/pull/164)).

### Fixed
- Return empty post list from Sophi response (props [@oscarssanchez](https://github.com/oscarssanchez), [@barryceelen](https://github.com/barryceelen), [@felipeelia](https://github.com/felipeelia) via [#183](https://github.com/globeandmail/sophi-for-wordpress/pull/183)).

### Security
- Update dependency `phpunit/phpunit` from 8.5.21 to 8.5.23 (props [@renovate](https://github.com/apps/renovate) via [#160](https://github.com/globeandmail/sophi-for-wordpress/pull/160)).
- Update dependency `prop-types` from 15.8.0 to 15.8.1 (props [@renovate](https://github.com/apps/renovate) via [#161](https://github.com/globeandmail/sophi-for-wordpress/pull/161)).
- Update dependency `10up-toolkit` from `1.0.13` to `2.1.1` (props [@renovate](https://github.com/apps/renovate), [@oscarssanchez](https://github.com/oscarssanchez), [@jeffpaul](https://github.com/jeffpaul) via [#169](https://github.com/globeandmail/sophi-for-wordpress/pull/169), [#189](https://github.com/globeandmail/sophi-for-wordpress/pull/189)).
- Update dependency `marked` from 2.1.3 to 4.0.10 (props [@renovate](https://github.com/apps/renovate) via [#176](https://github.com/globeandmail/sophi-for-wordpress/pull/176)).
- Update dependency `jsdoc` from 3.6.8 to 3.6.10 (props [@renovate](https://github.com/apps/renovate) via [#177](https://github.com/globeandmail/sophi-for-wordpress/pull/177)).
- Update dependency `dealerdirect/phpcodesniffer-composer-installer` from 0.7.1 to 0.7.2 (props [@renovate](https://github.com/apps/renovate) via [#182](https://github.com/globeandmail/sophi-for-wordpress/pull/182)).

## [1.0.8] - 2021-12-23
### Changed
- Updated `auth_url` and `audience` parameters to get respective Staging and Development environment access tokens (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia) via [#152](https://github.com/globeandmail/sophi-for-wordpress/pull/152)).

### Fixed
- Issue where multiple Sophi blocks on the same page had duplicated content (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia), [@jeffpaul](https://github.com/jeffpaul), [@dinhtungdu](https://github.com/dinhtungdu) via [#157](https://github.com/globeandmail/sophi-for-wordpress/pull/157)).
- Testing environment deploy process (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia) via [#155](https://github.com/globeandmail/sophi-for-wordpress/pull/155)).

### Security
- Update dependency `prop-types` from 15.7.2 to 15.8.0 (props [@renovate](https://github.com/marketplace/renovate) via [#158](https://github.com/globeandmail/sophi-for-wordpress/pull/158)).

## [1.0.7] - 2021-10-29
### Changed
- Sophi Auth URL value used for Production, Staging, and Development (props [@jeffpaul](https://github.com/jeffpaul), [@barryceelen](https://github.com/barryceelen), [@amckie](https://github.com/amckie) via [#148](https://github.com/globeandmail/sophi-for-wordpress/pull/148)).
- Sophi Site Automation API URL structure (props [@Rahmon](https://github.com/Rahmon) via [#149](https://github.com/globeandmail/sophi-for-wordpress/pull/149)).
- Sophi Audience URL used in authorization (props [@Rahmon](https://github.com/Rahmon) via [#150](https://github.com/globeandmail/sophi-for-wordpress/pull/150)).

## [1.0.6] - 2021-10-27
**Note: this was a hotfix release to fix an issue with deploys to WordPress.org.**

## [1.0.5] - 2021-10-27
### Added
- New content fields sent to Sophi `thumbnailImageUri`, `embeddedImagesCount`, and `keywords` (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia), [@dinhtungdu](https://github.com/dinhtungdu) via [#116](https://github.com/globeandmail/sophi-for-wordpress/pull/116)).

### Changed
- Updated name convention for `appId` (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia), [@dinhtungdu](https://github.com/dinhtungdu) via [#117](https://github.com/globeandmail/sophi-for-wordpress/pull/117)).
- Send WordPress Categories to Sophi in `sectionNames` field (props [@Rahmon](https://github.com/Rahmon), [@jeffpaul](https://github.com/jeffpaul), [@felipeelia](https://github.com/felipeelia), [@tott](https://github.com/tott) via [#135](https://github.com/globeandmail/sophi-for-wordpress/pull/135), [#138](https://github.com/globeandmail/sophi-for-wordpress/pull/138), [#140](https://github.com/globeandmail/sophi-for-wordpress/pull/140), [#142](https://github.com/globeandmail/sophi-for-wordpress/pull/142), [#144](https://github.com/globeandmail/sophi-for-wordpress/pull/144)).
- Updated JS tracking of the homepage from `article` to `section` content type (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia), [@jeffpaul](https://github.com/jeffpaul) via [#139](https://github.com/globeandmail/sophi-for-wordpress/pull/139), [#140](https://github.com/globeandmail/sophi-for-wordpress/pull/140), [#142](https://github.com/globeandmail/sophi-for-wordpress/pull/142)).
- Updated `audience` URL (props [@Rahmon](https://github.com/Rahmon), [@jeffpaul](https://github.com/jeffpaul) via [#143](https://github.com/globeandmail/sophi-for-wordpress/pull/143)).
- Bump WordPress version "tested up to" 5.8 (props [@Rahmon](https://github.com/Rahmon), [@jeffpaul](https://github.com/jeffpaul) via [#146](https://github.com/globeandmail/sophi-for-wordpress/pull/146)).
- Documentation (props [@dkotter](https://github.com/dkotter) via [#113](https://github.com/globeandmail/sophi-for-wordpress/pull/113)).

### Fixed
- Stopped sending homepage (aka "page on front" or "page for posts") content updates to Sophi (props [@Rahmon](https://github.com/Rahmon), [@felipeelia](https://github.com/felipeelia), [@jeffpaul](https://github.com/jeffpaul) via [#139](https://github.com/globeandmail/sophi-for-wordpress/pull/139), [#140](https://github.com/globeandmail/sophi-for-wordpress/pull/140), [#142](https://github.com/globeandmail/sophi-for-wordpress/pull/142)).

### Security
- Update dependency `10up-toolkit` from 1.0.9 to 1.0.13 (props [@renovate](https://github.com/marketplace/renovate) via [#111](https://github.com/globeandmail/sophi-for-wordpress/pull/111), [#115](https://github.com/globeandmail/sophi-for-wordpress/pull/115), [#129](https://github.com/globeandmail/sophi-for-wordpress/pull/129), [#145](https://github.com/globeandmail/sophi-for-wordpress/pull/145)).
- Update dependency `phpunit/phpunit` from 8.5.18 to 8.5.21 (props [@renovate](https://github.com/marketplace/renovate) via [#114](https://github.com/globeandmail/sophi-for-wordpress/pull/114), [#120](https://github.com/globeandmail/sophi-for-wordpress/pull/120), [#132](https://github.com/globeandmail/sophi-for-wordpress/pull/132)).
- Update dependency `automattic/vipwpcs` from 2.3.2 to 2.3.3 (props [@renovate](https://github.com/marketplace/renovate) via [#133](https://github.com/globeandmail/sophi-for-wordpress/pull/133)).

## [1.0.4] - 2021-07-29
### Added
- Support for Yoast canonical URL (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter) via [#70](https://github.com/globeandmail/sophi-for-wordpress/pull/70), [#71](https://github.com/globeandmail/sophi-for-wordpress/pull/71), [#72](https://github.com/globeandmail/sophi-for-wordpress/pull/72)).
- Configure WhiteSource Bolt and Renovate integrations (props [@whitesource-bolt](https://github.com/marketplace/whitesource-bolt), [@renovate](https://github.com/marketplace/renovate) via [#72](https://github.com/globeandmail/sophi-for-wordpress/pull/72), [#97](https://github.com/globeandmail/sophi-for-wordpress/pull/97)).

### Changed
- Updated AMP and JS tracking data, changed post data type to post content type (props [@dinhtungdu](https://github.com/dinhtungdu) via [#71](https://github.com/globeandmail/sophi-for-wordpress/pull/71), [#72](https://github.com/globeandmail/sophi-for-wordpress/pull/72)).
- Update documentation, dependencies, and pin dependencies (props [@jeffpaul](https://github.com/jeffpaul), [@dinhtungdu](https://github.com/dinhtungdu), [@renovate](https://github.com/marketplace/renovate) via [#96](https://github.com/globeandmail/sophi-for-wordpress/pull/96), [#98](https://github.com/globeandmail/sophi-for-wordpress/pull/98), [#104](https://github.com/globeandmail/sophi-for-wordpress/pull/104)).

### Fixed
- Issue with empty `sectionNames` (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter) via [#69](https://github.com/globeandmail/sophi-for-wordpress/pull/69)).
- Set `jsonschema` to 2.0.0 (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter) via [#69](https://github.com/globeandmail/sophi-for-wordpress/pull/69)).
- Corrected variable name from `contentSize` to `size` (props [@dinhtungdu](https://github.com/dinhtungdu) via [#71](https://github.com/globeandmail/sophi-for-wordpress/pull/71)).
- Sending publish events when Yoast SEO is activated (props [@dinhtungdu](https://github.com/dinhtungdu) via [#107](https://github.com/globeandmail/sophi-for-wordpress/pull/107)).
- Only use public taxonomies to build post breadcrumb (props [@dinhtungdu](https://github.com/dinhtungdu) via [#109](https://github.com/globeandmail/sophi-for-wordpress/pull/109)).
- Update events via Quick Edit are now sent to Sophi when Yoast SEO is activated (props [@dinhtungdu](https://github.com/dinhtungdu) via [#110](https://github.com/globeandmail/sophi-for-wordpress/pull/110)).

### Security
- Update dependency `@10up/scripts` from 1.3.1 to 1.3.4 (props [@renovate](https://github.com/marketplace/renovate) via [#99](https://github.com/globeandmail/sophi-for-wordpress/pull/99)).
- Update dependency `automattic/vipwpcs` from 2.3.0 to 2.3.2 (props [@renovate](https://github.com/marketplace/renovate) via [#100](https://github.com/globeandmail/sophi-for-wordpress/pull/100)).
- Update dependency `phpunit/phpunit` from 8.5.15 to 8.5.18 (props [@renovate](https://github.com/marketplace/renovate) via [#101](https://github.com/globeandmail/sophi-for-wordpress/pull/101), [#108](https://github.com/globeandmail/sophi-for-wordpress/pull/108)).
- Update `actions/setup-node` action from v1 to v2 (props [@renovate](https://github.com/marketplace/renovate) via [#102](https://github.com/globeandmail/sophi-for-wordpress/pull/102)).
- Update dependency `10up-toolkit` from 1.0.9 to 1.0.10 (props [@renovate](https://github.com/marketplace/renovate) via [#111](https://github.com/globeandmail/sophi-for-wordpress/pull/111)).

## [1.0.3] - 2021-06-15
### Added
- Data attributes to Site Automation widgets/blocks (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter) via [#64](https://github.com/globeandmail/sophi-for-wordpress/pull/64)).

### Changed
- Revisions to tracking data collected to improve Site Automation results (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter) via [#65](https://github.com/globeandmail/sophi-for-wordpress/pull/65)).
- Update default Collector URL helper text (props [@barryceelen](https://github.com/barryceelen) via [#56](https://github.com/globeandmail/sophi-for-wordpress/pull/56)).
- Set default environment according to `wp_get_environment_type()` (props [@barryceelen](https://github.com/barryceelen) via [#57](https://github.com/globeandmail/sophi-for-wordpress/pull/57)).

### Fixed
- Only load Snowplow analytics once Sophi plugin is configured (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter), [@barryceelen](https://github.com/barryceelen) via [#61](https://github.com/globeandmail/sophi-for-wordpress/pull/61)).
- VIP CLI dry-run mode defaults to `false`, corrects sync limiting, adds progress bar (props [@dinhtungdu](https://github.com/dinhtungdu), [@jeffpaul](https://github.com/jeffpaul), [@barryceelen](https://github.com/barryceelen) via [#66](https://github.com/globeandmail/sophi-for-wordpress/pull/66)).

## [1.0.2] - 2021-04-26
### Changed
- Bump `vipwpcs` from 2.2.0 to 2.3.0 and `php_codesniffer` from 3.5.8 to 3.6.0 (props [@dinhtungdu](https://github.com/dinhtungdu), [@jeffpaul](https://github.com/jeffpaul) via [#47](https://github.com/globeandmail/sophi-for-wordpress/pull/47)).

### Fixed
- WP-CLI command now supports both WordPress VIP and non-VIP environments (props [@dinhtungdu](https://github.com/dinhtungdu), [@dkotter](https://github.com/dkotter), [@jeffpaul](https://github.com/jeffpaul) via [#45](https://github.com/globeandmail/sophi-for-wordpress/pull/45)).

## [1.0.1] - 2021-04-23
### Added
- `noConfigFile` setting (props [@dinhtungdu](https://github.com/dinhtungdu) via [#48](https://github.com/globeandmail/sophi-for-wordpress/pull/48)).
- GitHub Actions to deploy releases and update readme/asset changes for WordPress.org (props [@jeffpaul](https://github.com/jeffpaul), [@dinhtungdu](https://github.com/dinhtungdu) via [#44](https://github.com/globeandmail/sophi-for-wordpress/pull/44)).

### Changed
- Renamed plugin from `Sophi for WordPress` to `Sophi` (props [@jeffpaul](https://github.com/jeffpaul) via [#49](https://github.com/globeandmail/sophi-for-wordpress/pull/49)).

### Fixed
- Minor fixes from WordPress VIP code scan (props [@dkotter](https://github.com/dkotter) via [#50](https://github.com/globeandmail/sophi-for-wordpress/pull/50)).

## [1.0.0] - 2021-04-14
- Initial public release! 🎉

[Unreleased]: https://github.com/globeandmail/sophi-for-wordpress/compare/trunk...develop
[1.0.13]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.12...1.0.13
[1.0.12]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.11...1.0.12
[1.0.11]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.10...1.0.11
[1.0.10]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.9...1.0.10
[1.0.9]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.8...1.0.9
[1.0.8]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.7...1.0.8
[1.0.7]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.6...1.0.7
[1.0.6]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.5...1.0.6
[1.0.5]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.4...1.0.5
[1.0.4]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.3...1.0.4
[1.0.3]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.2...1.0.3
[1.0.2]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/globeandmail/sophi-for-wordpress/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/globeandmail/sophi-for-wordpress/tree/3e714c0149a3b3e4a209c9d71b1510e43c42efcd
