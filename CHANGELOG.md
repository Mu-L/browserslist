# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

## 4.25.1
* Updated Firefox ESR.

## 4.25.0
* Added `cover 95% in browserslist-config-mycompany stats` query support.

## 4.24.5
* Fixed support ESM shared config.
* Fixed docs (by Alexander Pushkov & マルコメ).

## 4.24.4
* Improved performance by using caching better (by @thoughtspile).

## 4.24.3
* Updated Firefox ESR (by @fpapado).

## 4.24.2
* Clarify outdated `caniuse-lite` warning text.

## 4.24.1
* Added months since last `caniuse-lite` update to the warning (by @mezhnin).

## 4.24.0
* Added `browserslist.findConfigFile()` helper (by @JLHwung).

## 4.23.3
* Fixed `>=` query for `ios` (by @syi0808).

## 4.23.2
* Updated Firefox ESR.

## 4.23.1
* Fixed feature query with mobile to desktop when caniuse lags (by @steverep).

## 4.23.0
* Added `BROWSERSLIST_ROOT_PATH` (by @teleclimber).

## 4.22.3
* Fixed white spaces support in `supports` query (@g-plane).
* Fixed shared config like `@company/package/browserslist-config` (@boucodes).

## 4.22.2
* Fixed idempotency in time queries with `mobileToDesktop` (by Aliaksei Sapach).

## 4.22.1
* Updated Firefox ESR (by @lerkor).

## 4.22
* Added `fully supports` query (by Ben Scott).
* Added `partially supports` alias for `supports` query (by Ben Scott).

## 4.21.11
* Added warning to `--update-db` to move to new CLI (by Ivan Vasilev).
* Fixed docs (by Tatsunori Uchino).

## 4.21.10
* Updated Firefox ESR.

## 4.21.9
* Fixed Opera Mobile edge cases (by Steve Repsher).

## 4.21.8
* Fixed `supports` query and `mobileToDesktop` (by Steve Repsher).

## 4.21.7
* Fixed last queries for Android (by Steve Repsher).

## 4.21.6
* Fixed time queries with `mobileToDesktop` (by Steve Repsher).
* Fixed docs (by Tatsunori Uchino, Will Stone, and Dominik Pschenitschni).

## 4.21.5
* Fixed running Browserslist in browser environment.

## 4.21.4
* Updated Firefox ESR.

## 4.21.3
* Improved unknown region and unknown feature error (by Alexander Chabin).

## 4.21.2
* Updated Firefox ESR.

## 4.21.1
* Fixed parsing days in `since` query.

## 4.21
* IE 11 was added to `dead` and removed from `defaults` (by Albert Portnoy).
* Added `browserslist.parse()` to get config AST for analysis.
* Moved `--update-db` script to `update-browserslist-db` tool.
* Fixed Unicode BOM support in `package.json`.

## 4.20.4
* Fixed Opera in `mobileToDesktop` (by Pig Fang).

## 4.20.3
* Added `Baidu` to `dead` browsers (by Igor Lukanin).

## 4.20.2
* Fixed `package.funding` URL format.

## 4.20.1
* Fixed `package.funding`.
* Fixed docs (by Michael Lohmann).

## 4.20
* Added `last 2 node versions` and `last 2 node major versions` (by @g-plane).

## 4.19.3
* Updated Firefox ESR (by Christophe Coevoet).

## 4.19.2
* Fixed `--help` output.

## 4.19.1
* Fixed `throwOnMissing` types (by Øyvind Saltvik).

## 4.19
* Added queries grammar definition (by Pig Fang).
* Added `throwOnMissing` option (by Øyvind Saltvik).
* Fixed `null` data ignoring in `< 50% in CN` (byPig Fang).
* Fixed data parsing in `in my stats` (by Sun Xiaoran).
* Fixed `yarn.lock` support with `integrity` (by Alexey Berezin).
* Fixed Yarn Berry error message in `--update-db`.

## 4.18.1
* Fixed case inventiveness for `cover` queries (by Pig Fang).
* Fixed `since 1970` query for `null` in release date (by Pig Fang).

## 4.18
* Added `--ignore-unknown-versions` CLI option (by Pig Fang).

## 4.17.6
* Fixed sharable config resolution (by Adaline Valentina Simonian).

## 4.17.5
* Fixed `--update-db` for some `pnpm` cases.

## 4.17.4
* Reduced package size.

## 4.17.3
* Use `picocolors` for color output in `--update-db`.

## 4.17.2
* Reduced package size.

## 4.17.1
* Use Nano Colors for color output in `--update-db`.

## 4.17
* Added `yarn` 3 support to `--update-db` (by Himank Pathak).

## 4.16.8
* Updated Firefox ESR.

## 4.16.7
* Fixed `oudated caniuse-lite` warning text (by Paul Verest).
* Fixed docs (by Alexander Belov).

## 4.16.6
* Fixed `npm-shrinkwrap.json` support in `--update-db` (by Geoff Newman).

## 4.16.5
* Fixed unsafe RegExp (by Yeting Li).

## 4.16.4
* Fixed unsafe RegExp.
* Added artifactory support to `--update-db` (by Ittai Baratz).

## 4.16.3
* Fixed `--update-db`.

## 4.16.2
* Fixed `--update-db` (by @ialarmedalien).

## 4.16.1
* Fixed Chrome 4 with `mobileToDesktop` (by Aron Woost).

## 4.16
* Add `browserslist config` query.

## 4.15
* Add TypeScript types (by Dmitry Semigradsky).

## 4.14.7
* Fixed Yarn Workspaces support to `--update-db` (by Fausto Núñez Alberro).
* Added browser changes to `--update-db` (by @AleksandrSl).
* Added color output to `--update-db`.
* Updated `package.funding` to have link to our Open Collective.

## 4.14.6
* Fixed Yarn support in `--update-db` (by Ivan Storck).
* Fixed npm 7 support in `--update-db`.

## 4.14.5
* Fixed `last 2 electron versions` query (by Sergey Melyukov).

## 4.14.4
* Fixed `Unknown version 59 of op_mob` error.

## 4.14.3
* Update Firefox ESR.

## 4.14.2
* Fixed `--update-db` on Windows (by James Ross).
* Improved `--update-db` output.

## 4.14.1
* Added `--update-db` explanation (by Justin Zelinsky).

## 4.14
* Add `BROWSERSLIST_DANGEROUS_EXTEND` support (by Timo Mayer).

## 4.13
* Added `supports` query to select browsers (by Jesús Leganés-Combarro).

## 4.12.2
* Update Firefox ESR.

## 4.12.1
* Update `package.json` scanning tool for `--update-db` (by Luke Edwards).
* Improve docs (by Mukundan Senthil).
* Drop Node.js 13.0-13.6 support because of ES modules bug in that versions.

## 4.12
* Add environments to shared configs (by Yevgeny Petukhov).
* Fix docs (by Dmitry Statsenko and Thomas Pozzo di Borgo).

## 4.11.1
* Fix Node.js 6 support.

## 4.11
* Add `npx browserslist --mobile-to-desktop` (by James Ross).

## 4.10
* Add `npx browserslist --update-db` (by Ivan Solovev).

## 4.9.1
* Normalize incorrect Can I Use regional data (by Huáng Jùnliàng).

## 4.9
* Add `node X-Y` query support (by Yuping Zuo).

## 4.8.7
* Fix `last N major versions` (by Valeriy Trubachev).

## 4.8.6
* Fix `Unknown version 10 of op_mob` error in `mobileToDesktop` option.

## 4.8.5
* Fix `last N browsers` again after new `caniuse-db` API changes.

## 4.8.4
* Fix released versions detection for queries like `last N browsers`.
* Add IE 11 Mobile to `dead` browsers.

## 4.8.3
* Fix warning message (by Anton Ivanov).

## 4.8.2
* Fix `Cannot convert undefined or null to object` (by Antoine Clausse).
* Fix `mobileToDesktop` in `defaults` (by Huáng Jùnliàng).

## 4.8.1
* Fix Chrome and `mobileToDesktop` (by Huáng Jùnliàng).

## 4.8
* Add `> 5% in browserslist-config-my stats` query (by Andrew Leedham).
* Improve docs (by Danny van Kooten).

## 4.7.3
* Add funding link for `npm fund`.

## 4.7.2
* Add cache for query parsing.
* Improve config caching (by Kārlis Gaņģis).
* Update Firefox ESR.

## 4.7.1
* Improve caching.

## 4.7
* Add PhantomJS queries.
* Improve docs (by Dorian Koehring).

## 4.6.6
* Remove Safari from `dead` query.

## 4.6.5
* Add Samsung 4 browser to `dead` query.
* Remove dirty fix for `android all` error.

## 4.6.4
* Add Firefox 68 to `Firefox ESR` query.

## 4.6.3
* Dirty fix for `android all` error.

## 4.6.2
* Fix `last x version` and similar queries for Android (by Tony Ross).

## 4.6.1
* Fix patch version support for Electron (by Kilian Valkhof).

## 4.6
* Add `mobileToDesktop` option (by Nicolò Ribaudo).

## 4.5.6
* Make `Node > 5` and `node > 5` queries case insensitive.

## 4.5.5
* Fix CLI help (by Marcel Gerber).
* Add KaiOS browser to docs.

## 4.5.4
* Update docs (by Andrew Leedham and Dan Onoshko).

## 4.5.3
* Fix splitting string to queries.

## 4.5.2
* Show default browsers in CLI on project without config.

## 4.5.1
* Improve text for the warning about outdated `caniuse-lite`.

## 4.5
* Add `>=`, `>`, and `<=` support for Node.js version (by Mathspy Terabithian).

## 4.4.2
* Allow to have string in `package.json` (by @dmarkhas).

## 4.4.1
* Allow to use `.` in scope name of shareable config (by Gustav Nikolaj).

## 4.4
* Added `and` and `or` keywords to combine queries (by Jon Ege Ronnenberg).

## 4.3.7
* Fix fraction years support in `last 1.5 years` (by Clément P).
* Fix version-less browser support.

## 4.3.6
* Fix version-less browser support in custom statistics (by Alex Walter).

## 4.3.5
* Fix `not` query for wrong Can I Use data.

## 4.3.4
* Allow to update `node-releases` without new Browserslist releases.

## 4.3.3
* Fix Node.js 11 support.

## 4.3.2
* Fix `Unknown version 11 of Node.js` error (by Dan Onoshko).

## 4.3.1
* Fix conflict between `caniuse-lite` and custom browsers statistics.

## 4.3
* Allow to use `extends browserslist-config-a/file` (by @Schweinepriester).

## 4.2.1
* Use new `node-releases` support (by Sergey Rubanov).

## 4.2
* Add `--json` argument for CLI.
* Allow to pass multiple areas in CLI by `--coverage=US,alt-AS,global`.

## 4.1.2
* Better `unknow query` error message.
* Use latest `node-releases`.

## 4.1.1
* Update Firefox ESR versions.

## 4.1
* Add `current node` query.
* Add contributors widget to docs (by Sergey Surkov).

## 4.0.2
* Fix new `node-releases` support (by Sergey Rubanov).
* Fix error text (by Josh Smith).

## 4.0.1
* Reduce npm package size.
* Fix docs.

## 4.0.0 “Erinaceus amurensis”
* Add `node X` and `maintained node versions` queries (by Pavel Vostrikov).
* Remove Node.js 4 support.
* Show warning if `caniuse-lite` is old (by Anton Tuzhik).
* Add comma support in config file.

## 3.2.8
* Add IE 9-5.5 to dead browsers.
* Remove development configs from npm package.

## 3.2.7
* Add Firefox 60 as Firefox ESR.

## 3.2.6
* Add Opera Mini 12 to dead browsers.
* Update docs (by Jamie Kyle).

## 3.2.5
* Fix excluding Opera Mini and other browsers with `all` version.

## 3.2.4
* Resolve shareable config from current working directory.

## 3.2.3
* Fix `package.json` config validation for single string case.
* Fix CLI error reporting.

## 3.2.2
* Add `package.json` config validation.
* Move project to `browserlist` GitHub organization.

## 3.2.1
* Fix error text (by Steve Schrab).

## 3.2
* Add `cover 99%` query (by Vasily Fedoseyev).
* Add `cover 99% in US` query (by Vasily Fedoseyev).
* Add `cover 99% in my stats` query (by Vasily Fedoseyev).
* Add `"my stats"` support to `browserlist.coverage()` (by Vasily Fedoseyev).

## 3.1.2
* Add more clear error on missed browser version.

## 3.1.1
* Fix JSDoc (by Sylvain Pollet-Villard).

## 3.1
* Add `ignoreUnknownVersions` option.
* Fix docs (by Pascal Duez).

## 3.0 “Atelerix sclateri”
* Remove country statistics from client-side build of Browserslist.
* Change `> 1%` to `> 0.5%` in default query.
* Add `not dead` to default query.
* Change default environment to `production` (by Marco Fugaro).
* Add `dead` query support with IE 10 and BlackBerry browser.
* Add multiple environments in one section support (by Evilebot Tnawi).
* Add custom statistics support to `browserlist.coverage()`.
* Fix `path` option check.

## 2.11.3
* Fix for `path: undefined` option.

## 2.11.2
* Remove Node.js specific code from webpack build.

## 2.11.1
* Fix using Browserslist in browser with `path` but without `fs`.

## 2.11
* Add `last 2 years` query support (by James Harris).

## 2.10.2
* Fix Browserify support.

## 2.10.1
* Fix using Browserslist without `process` (by Andrew Patton).

## 2.10
* Add `< 1%` and `<= 1%` queries support (by August Kaiser).

## 2.9.1
* Fix unknown query on trailing spaces in query.

## 2.9
* Add `last Electron versions` and `last Electron major versions` queries
  (by Louis Mouhat).

## 2.8
* Add `since 2016-03` and `since 2016-03-20` queries support (by Andrew Blick).

## 2.7
* Add `since 2016` queries support (by Igor Deryabin).

## 2.6.1
* Fix `Path must be a string` error.

## 2.6
* By default load config from current directory in CLI tool.

## 2.5.1
* Allow `@scope/browserlist-config` config name (by Jamie Connolly).

## 2.5
* Add `extends` query (by YellowKirby).

## 2.4.1
* Throw error if `package.json` contain `browserlist` instead of `browserslist`.

## 2.4
* Add `last n major versions` query (by John Sanders).

## 2.3.3
* Fix browsers support.

## 2.3.2
* Fix `> 0` query for browsers with one version (by Nikolay Solovyov).

## 2.3.1
* Reduce library size.

## 2.3
* Add `unreleased versions` and `unreleased Chrome versions` queries.

## 2.2.2
* Fix `Path must be a string` error (by Pieter Beulque).

## 2.2.1
* Fix security issue with regions dynamic `require`.

## 2.2
* Add region usage statistics support (by Clément P).

## 2.1.5
* Remove Firefox 45 from Firefox ESR.

## 2.1.4
* Use both ESR versions when they actual.

## 2.1.3
* Add warning on first exclude query.

## 2.1.2
* Fix non-Node.js environments support.

## 2.1.1
* Fix CLI arguments parsing.

## 2.1
* Add `>= 5%`, `>= 5% in US` and `>= 5% in my stats` queries.

## 2.0 “Atelerix frontalis”
* `last n versions` returns versions for all browsers, not only main browsers.
* Cache file system operations (by Aarni Koskela).
* Use `caniuse-lite` 1 MB instead of `caniuse-db` 7 MB (by Ben Briggs).
* Add `.browserslistrc` config support.
* Add QQ Browser for Android support.
* Add tests for CLI (by Zhulduz Zhankenova).

## 1.7.7
* Update Firefox ESR.

## 1.7.6
* Fix Android Chrome selection.

## 1.7.5
* Fix combining `not` query with country based statistics.
* Fix `--env` argument in CLI (by Tuure Savuoja).

## 1.7.4
* Speed up browser sorting (by Aarni Koskela).

## 1.7.3
* Fix config finding when directory was passed to `path` (by Aarni Koskela).

## 1.7.2
* Fix config finding algorithm (by Aarni Koskela).

## 1.7.1
* Fix unreleased browsers version detection.

## 1.7
* Add `--config` and `--env` arguments to CLI (by Jarek Rencz).

## 1.6
* Convert Electron version to Chrome (by Kilian Valkhof).
* Fix `0` version mistake in Can I Use data.

## 1.5.2
* Fix browser versions ordering (by Marco Massarotto).

## 1.5.1
* Fix error on `package.json` and `browserslist` in same directory.

## 1.5
* Add `package.json` support (by Stepan Kuzmin).
* Add environments support (by Maksim Semenov and openlibser).
* Add `browserslist-stats.json` file support (by Oleh Aloshkin).
* Add `config` option to CLI (by Evilebot Tnawi).
* Add JSDoc.
* Fix tests on Windows (by Anna Stoliar).
* Don’t set custom usage statistics globally.

## 1.4
* Add `defaults` keyword.

## 1.3.6
* Add `UCAndroid` alias to `and_uc` (by Evilebot Tnawi).

## 1.3.5
* Fix Opera Mini support. Use `op_mini all`.

## 1.3.4
* Add space-less `>1%` and `>.5%` syntax support (by Andreas Lind).

## 1.3.3
* Clean `0` versions in some country-based requests.

## 1.3.2
* Update Firefox ESR.

## 1.3.1
* Add Safari TP support.

## 1.3
* Add coverage for specific country (by Joshua Wise).

## 1.2
* Add `browserslist.coverage()` method.
* Add `--coverage` and `-c` argument to CLI.
* Add `-v` argument support to CLI.
* Better error handling in CLI.

## 1.1.3
* Fix jspm support (by Sean Anderson).

## 1.1.2
* Fix jspm support (by Sean Anderson).

## 1.1.1
* Fix space-less `>10%` and `>10% in my stats` queries.
* Normalize error messages.
* Remove development files from npm package.

## 1.1
* Added query against custom browser usage data (by Daniel Rey).

## 1.0.1
* Update Firefox ESR (by Rouven Weßling).

## 1.0 “Atelerix algirus”
* Remove Opera 12.1 from default query.
* Add `not` keyword and exclude browsers by query.
* Add Microsoft Edge support (by Andrey Polischuk).
* Add CLI for debug and non-JS usage (by Luke Horvat).
* Use own class in Browserslist errors.

## 0.5
* Add version ranges `IE 6-9` (by Ben Briggs).

## 0.4
* Add `config` option and `BROWSERSLIST_CONFIG` environment variable support.
* Add symlink config support.

## 0.3.3
* Fix DynJS compatibility (by Nick Howes).

## 0.3.2
* Fix joined versions on versions query (by Vincent De Oliveira).

## 0.3.1
* Fix global variable leak (by Peter Müller).

## 0.3
* Takes queries from `BROWSERSLIST` environment variable.

## 0.2
* Return Can I Use joined versions as `ios_saf 7.0-7.1`.

## 0.1.3
* Better work with Can I Use joined versions like `ios_saf 7.0-7.1`.
* Browserslist now understands `ios_saf 7.0` or `ios_saf 7`.

## 0.1.2
* Do not create global `browserslist` var (by Maxime Thirouin).

## 0.1.1
* Sort browsers by name and version.

## 0.1 “Atelerix albiventris”
* Initial release.
