# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.9.2"></a>
## [0.9.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.9.1...v0.9.2) (2018-02-02)


### Bug Fixes

* **dialog:** workarround fixed element position issue whith transform ([c658ff9](https://github.com/stasson/vue-mdc-adapter/commit/c658ff9)), closes [#238](https://github.com/stasson/vue-mdc-adapter/issues/238)
* **select:** select model should be reactive ([2dea85c](https://github.com/stasson/vue-mdc-adapter/commit/2dea85c)), closes [#239](https://github.com/stasson/vue-mdc-adapter/issues/239)


### Features

* **textfield:** add focus/blur method ([975033b](https://github.com/stasson/vue-mdc-adapter/commit/975033b))



<a name="0.9.1"></a>
## [0.9.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.9.0...v0.9.1) (2018-01-31)


### Bug Fixes

* **list:** make props reactive ([bb6aeea](https://github.com/stasson/vue-mdc-adapter/commit/bb6aeea)), closes [#231](https://github.com/stasson/vue-mdc-adapter/issues/231)
* **select:** make disabled prop reactive ([6da65cc](https://github.com/stasson/vue-mdc-adapter/commit/6da65cc)), closes [#231](https://github.com/stasson/vue-mdc-adapter/issues/231)
* **switch:** make alignEnd prop reactive ([61380ef](https://github.com/stasson/vue-mdc-adapter/commit/61380ef)), closes [#231](https://github.com/stasson/vue-mdc-adapter/issues/231)


### Features

* **list:** add mdc-list-item selected and activated property ([cccda1d](https://github.com/stasson/vue-mdc-adapter/commit/cccda1d)), closes [#235](https://github.com/stasson/vue-mdc-adapter/issues/235)



<a name="0.9.0"></a>
# [0.9.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.8.3...v0.9.0) (2018-01-27)


### Bug Fixes

* **package:** update material-components-web to version 0.29.0 ([f13d0b5](https://github.com/stasson/vue-mdc-adapter/commit/f13d0b5))
* **select:** fix stylelint issues ([a03c907](https://github.com/stasson/vue-mdc-adapter/commit/a03c907))
* **select:** multi select styles removed from mdc 0.29.0 ([44b8711](https://github.com/stasson/vue-mdc-adapter/commit/44b8711))
* **texfield:** update textfield adapters as per mdc 0.29.0 ([d565a31](https://github.com/stasson/vue-mdc-adapter/commit/d565a31))
* **textfield:** make helptext-persistent and helptext-validation props persitent ([85811a9](https://github.com/stasson/vue-mdc-adapter/commit/85811a9)), closes [#231](https://github.com/stasson/vue-mdc-adapter/issues/231)


### Features

* **list:** add support for interactive prop, default to non-interactive ([d3b9edb](https://github.com/stasson/vue-mdc-adapter/commit/d3b9edb)), closes [#224](https://github.com/stasson/vue-mdc-adapter/issues/224)



<a name="0.8.3"></a>
## [0.8.3](https://github.com/stasson/vue-mdc-adapter/compare/v0.8.2...v0.8.3) (2018-01-21)


### Bug Fixes

* **select:** set menu styles synchronuously ([9a9a1b6](https://github.com/stasson/vue-mdc-adapter/commit/9a9a1b6))


### Features

* **drawer:** add openOn and closeOn property ([ec1ef88](https://github.com/stasson/vue-mdc-adapter/commit/ec1ef88))



<a name="0.8.2"></a>
## [0.8.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.8.1...v0.8.2) (2018-01-19)


### Bug Fixes

* Component properties ([f3fcff4](https://github.com/stasson/vue-mdc-adapter/commit/f3fcff4))
* **textfield:** textarea model value ignored ([737e391](https://github.com/stasson/vue-mdc-adapter/commit/737e391)), closes [#215](https://github.com/stasson/vue-mdc-adapter/issues/215)


### Features

* add name property to texfield, checkbox, select, switch ([0de50f9](https://github.com/stasson/vue-mdc-adapter/commit/0de50f9)), closes [#212](https://github.com/stasson/vue-mdc-adapter/issues/212)



<a name="0.8.1"></a>
## [0.8.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.8.0...v0.8.1) (2018-01-16)


### Bug Fixes

* **textfield:** add missing type attribute ([fb796aa](https://github.com/stasson/vue-mdc-adapter/commit/fb796aa)), closes [#210](https://github.com/stasson/vue-mdc-adapter/issues/210)



<a name="0.8.0"></a>
# [0.8.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.6...v0.8.0) (2018-01-13)


### Bug Fixes

* **base:** custom link and button should dispatch click event when rendering router-link ([bfd3e5a](https://github.com/stasson/vue-mdc-adapter/commit/bfd3e5a)), closes [#206](https://github.com/stasson/vue-mdc-adapter/issues/206)
* **drawer-item:** emit click event regardless of router link presence ([217413f](https://github.com/stasson/vue-mdc-adapter/commit/217413f)), closes [#206](https://github.com/stasson/vue-mdc-adapter/issues/206)
* **package:** update material-components-web to version 0.28.0 ([73eae0e](https://github.com/stasson/vue-mdc-adapter/commit/73eae0e))


### Features

* **drawer:** refactor classes as per mdc 0.28.0 ([6a9dc05](https://github.com/stasson/vue-mdc-adapter/commit/6a9dc05))
* **icon-toggle:** remove primary property as per mdc 0.28.0 ([69c983a](https://github.com/stasson/vue-mdc-adapter/commit/69c983a))
* **list:** add new padded prop to list-deivider as per mdc 0.28.0 ([21f3a2f](https://github.com/stasson/vue-mdc-adapter/commit/21f3a2f))
* **menu:** refactor adapter as per mdc 0.28.0 ([6d0e0c1](https://github.com/stasson/vue-mdc-adapter/commit/6d0e0c1))
* **ripple:** refactor adapter as per mdc 0.28.0 ([10afb2e](https://github.com/stasson/vue-mdc-adapter/commit/10afb2e))
* **select:** refactor markup and adapter as per mdc 0.28.0 ([a7e29d5](https://github.com/stasson/vue-mdc-adapter/commit/a7e29d5))
* **snackbar:** add show and hide event as per mdc 0.28.0 ([eb372d2](https://github.com/stasson/vue-mdc-adapter/commit/eb372d2))
* **tabs:** add support for vue-router and custom icons ([38d2d51](https://github.com/stasson/vue-mdc-adapter/commit/38d2d51)), closes [#195](https://github.com/stasson/vue-mdc-adapter/issues/195)
* **text-field:** add text-field--box support ([40a03ce](https://github.com/stasson/vue-mdc-adapter/commit/40a03ce))
* **textfield:** add support for leading and trailing icons ([f95274e](https://github.com/stasson/vue-mdc-adapter/commit/f95274e)), closes [#174](https://github.com/stasson/vue-mdc-adapter/issues/174)
* **textfield:** refactor foundation and markup as per mdc 0.28.0 ([70dfab9](https://github.com/stasson/vue-mdc-adapter/commit/70dfab9))



<a name="0.7.6"></a>
## [0.7.6](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.5...v0.7.6) (2018-01-07)


### Features

* **button:** add button accent property ([fd3e124](https://github.com/stasson/vue-mdc-adapter/commit/fd3e124)), closes [#147](https://github.com/stasson/vue-mdc-adapter/issues/147)
* **button:** add support for vue-router ([43a9d3f](https://github.com/stasson/vue-mdc-adapter/commit/43a9d3f))
* **card:** add accent property to mdc-card action ([01a0f7e](https://github.com/stasson/vue-mdc-adapter/commit/01a0f7e))
* **card:** add vue-router support for action button ([52ddaf2](https://github.com/stasson/vue-mdc-adapter/commit/52ddaf2))
* **fab:** add support for vue-router ([383dffa](https://github.com/stasson/vue-mdc-adapter/commit/383dffa))



<a name="0.7.5"></a>
## [0.7.5](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.4...v0.7.5) (2018-01-07)


### Bug Fixes

* **webpack:** common chunks plugin typo ([014df1f](https://github.com/stasson/vue-mdc-adapter/commit/014df1f))


### Features

* **checkbox:** allow custom label markup ([3bf6547](https://github.com/stasson/vue-mdc-adapter/commit/3bf6547)), closes [#185](https://github.com/stasson/vue-mdc-adapter/issues/185)
* **switch:** allow custom label markup with default slot ([e89a618](https://github.com/stasson/vue-mdc-adapter/commit/e89a618))



<a name="0.7.4"></a>
## [0.7.4](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.3...v0.7.4) (2018-01-05)


### Bug Fixes

* **drawer:** make responsive behaviour consistent ([9b1395a](https://github.com/stasson/vue-mdc-adapter/commit/9b1395a)), closes [#76](https://github.com/stasson/vue-mdc-adapter/issues/76)
* **drawer:** toolbar spacer should be  inside the mdc-drawer__drawer element [#187](https://github.com/stasson/vue-mdc-adapter/issues/187) ([e45a8f0](https://github.com/stasson/vue-mdc-adapter/commit/e45a8f0))
* **select:** select with pre-selected option doesn't float label [#188](https://github.com/stasson/vue-mdc-adapter/issues/188) ([f296d42](https://github.com/stasson/vue-mdc-adapter/commit/f296d42))


### Features

* add focus/blur events to inputs ([4c99d44](https://github.com/stasson/vue-mdc-adapter/commit/4c99d44)), closes [#181](https://github.com/stasson/vue-mdc-adapter/issues/181)
* distribution should have a version [#129](https://github.com/stasson/vue-mdc-adapter/issues/129) ([a9bf69d](https://github.com/stasson/vue-mdc-adapter/commit/a9bf69d))



<a name="0.7.3"></a>
## [0.7.3](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.2...v0.7.3) (2017-12-29)


### Bug Fixes

* **layout-app:** use display:block for ie11 ([de40002](https://github.com/stasson/vue-mdc-adapter/commit/de40002))



<a name="0.7.2"></a>
## [0.7.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.1...v0.7.2) (2017-12-29)


### Bug Fixes

* **layout-app:** flex min-height workarround vor ie11 ([4aea0ce](https://github.com/stasson/vue-mdc-adapter/commit/4aea0ce)), closes [#176](https://github.com/stasson/vue-mdc-adapter/issues/176)
* **textfield:** mdc-textfield should be inline-flex ([8d2d256](https://github.com/stasson/vue-mdc-adapter/commit/8d2d256)), closes [#166](https://github.com/stasson/vue-mdc-adapter/issues/166)



<a name="0.7.1"></a>
## [0.7.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.7.0...v0.7.1) (2017-12-29)


### Bug Fixes

* **demo:** add missing meta tags ([5c5f2b4](https://github.com/stasson/vue-mdc-adapter/commit/5c5f2b4))
* **demo:** fix logo size for ie11 ([ffb154d](https://github.com/stasson/vue-mdc-adapter/commit/ffb154d))


### Features

* **demo:** add compatibility meta tag ([a555a9d](https://github.com/stasson/vue-mdc-adapter/commit/a555a9d))
* **demo:** add ie11 support ([def1985](https://github.com/stasson/vue-mdc-adapter/commit/def1985))
* **drawer:** add drawer-type prop for easy drawer type switching ([ae97d16](https://github.com/stasson/vue-mdc-adapter/commit/ae97d16)), closes [#132](https://github.com/stasson/vue-mdc-adapter/issues/132)
* remove need for polyfill on ie11 ([e39f6b9](https://github.com/stasson/vue-mdc-adapter/commit/e39f6b9)), closes [#168](https://github.com/stasson/vue-mdc-adapter/issues/168)
* **textfield:** emit blur event from input or textarea element ([697b782](https://github.com/stasson/vue-mdc-adapter/commit/697b782)), closes [#172](https://github.com/stasson/vue-mdc-adapter/issues/172)



<a name="0.7.0"></a>
# [0.7.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.5...v0.7.0) (2017-12-19)


### Bug Fixes

* **list:** Correct "mdc-list-item__secondary-text" ([308ea01](https://github.com/stasson/vue-mdc-adapter/commit/308ea01))
* **package:** update material-components-web to version 0.27.0 ([005c08e](https://github.com/stasson/vue-mdc-adapter/commit/005c08e))
* **select:** mdc 0.27.0 styles issues workarrounds ([4f37bd6](https://github.com/stasson/vue-mdc-adapter/commit/4f37bd6))
* **textfield:** label should be transparent ([d22cf3c](https://github.com/stasson/vue-mdc-adapter/commit/d22cf3c))


### Features

* **docs:** add style guide ([2334b74](https://github.com/stasson/vue-mdc-adapter/commit/2334b74))
* **drawer:** implement mdc v0.27.0 ([a3e3e3e](https://github.com/stasson/vue-mdc-adapter/commit/a3e3e3e))
* **drawer:** temporary drawer should be auto-scrollable [#159](https://github.com/stasson/vue-mdc-adapter/issues/159) ([d9588b5](https://github.com/stasson/vue-mdc-adapter/commit/d9588b5))
* **list:** implement mdc v0.27.0 ([b35cad7](https://github.com/stasson/vue-mdc-adapter/commit/b35cad7))
* **menu:** implement mdc v0.27.0 ([1179781](https://github.com/stasson/vue-mdc-adapter/commit/1179781))
* **radio:** mdc-radio's init should follow v-model when checked prop is unset? [#155](https://github.com/stasson/vue-mdc-adapter/issues/155) ([5e3263d](https://github.com/stasson/vue-mdc-adapter/commit/5e3263d))
* **select:** implement mdc v0.27.0 ([5247b59](https://github.com/stasson/vue-mdc-adapter/commit/5247b59))
* **textfield:** implement mdc v0.27.0 ([dbf39f8](https://github.com/stasson/vue-mdc-adapter/commit/dbf39f8))



<a name="0.6.5"></a>
## [0.6.5](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.4...v0.6.5) (2017-12-07)


### Bug Fixes

* **drawer:** temporary drawer should close on item click ([0d9017c](https://github.com/stasson/vue-mdc-adapter/commit/0d9017c))
* **icon-toggle:** Custom Icons Don't work [#150](https://github.com/stasson/vue-mdc-adapter/issues/150) ([0a5f454](https://github.com/stasson/vue-mdc-adapter/commit/0a5f454))



<a name="0.6.4"></a>
## [0.6.4](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.3...v0.6.4) (2017-12-06)



<a name="0.6.3"></a>
## [0.6.3](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.2...v0.6.3) (2017-12-06)



<a name="0.6.2"></a>
## [0.6.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.1...v0.6.2) (2017-12-06)


### Bug Fixes

* **demo:** rename iframe iports as per new distribution ([7688a86](https://github.com/stasson/vue-mdc-adapter/commit/7688a86))



<a name="0.6.1"></a>
## [0.6.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.6.0...v0.6.1) (2017-12-06)


### Bug Fixes

* **dist:** add missing source distribution and fix unpkg name ([28980e7](https://github.com/stasson/vue-mdc-adapter/commit/28980e7))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.5.3...v0.6.0) (2017-12-06)


### Bug Fixes

* **checkbox:** checkbox throws error if no label [#135](https://github.com/stasson/vue-mdc-adapter/issues/135) ([c3e7c97](https://github.com/stasson/vue-mdc-adapter/commit/c3e7c97))
* **tabs:** Fixing mdc-tab-bar bar property reference [#148](https://github.com/stasson/vue-mdc-adapter/issues/148) ([943d851](https://github.com/stasson/vue-mdc-adapter/commit/943d851))


### build

* **dist:** simplify webpack config as per new ESM distribution ([309bcd6](https://github.com/stasson/vue-mdc-adapter/commit/309bcd6))
* **sass:** add sass theme to distribution ([3f66f4e](https://github.com/stasson/vue-mdc-adapter/commit/3f66f4e))


### Features

* **button:** make all props reactive ([1b1a06b](https://github.com/stasson/vue-mdc-adapter/commit/1b1a06b))
* **demo:** add vue-analytics ([c25cf84](https://github.com/stasson/vue-mdc-adapter/commit/c25cf84))
* **dist:** add esm distribution for bundlers ([be55a74](https://github.com/stasson/vue-mdc-adapter/commit/be55a74))
* **dist:** add esm distribution for bundlers ([e55dd5b](https://github.com/stasson/vue-mdc-adapter/commit/e55dd5b))
* **theme:** implement mdc-theme ([385ca64](https://github.com/stasson/vue-mdc-adapter/commit/385ca64))


### BREAKING CHANGES

* **sass:** components source are not distributed. use sass from dist folder.
* **dist:** UMD distribution names have changed. see docs/getting-started.md



<a name="0.5.3"></a>
## [0.5.3](https://github.com/stasson/vue-mdc-adapter/compare/v0.5.2...v0.5.3) (2017-11-29)


### Bug Fixes

* **demo:** demo styles are not selected on production build ([16dcc93](https://github.com/stasson/vue-mdc-adapter/commit/16dcc93))



<a name="0.5.2"></a>
## [0.5.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.5.1...v0.5.2) (2017-11-29)


### Bug Fixes

* **package:** fix unpkg field to new /dist/index.js ([917d528](https://github.com/stasson/vue-mdc-adapter/commit/917d528))


### Features

* **drawer:** add support for router-link mode ([45b6796](https://github.com/stasson/vue-mdc-adapter/commit/45b6796))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.5.0...v0.5.1) (2017-11-28)


### Bug Fixes

* **demo:** set iframe elevation to 1 ([1662382](https://github.com/stasson/vue-mdc-adapter/commit/1662382))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.4.2...v0.5.0) (2017-11-28)


### Bug Fixes

* enforce class name convention ([5660b39](https://github.com/stasson/vue-mdc-adapter/commit/5660b39)), closes [#121](https://github.com/stasson/vue-mdc-adapter/issues/121)
* enforce component naming convention ([8f805c5](https://github.com/stasson/vue-mdc-adapter/commit/8f805c5))
* **package:** update material-components-web to version 0.26.0 ([d1f6da5](https://github.com/stasson/vue-mdc-adapter/commit/d1f6da5))
* **select:** size property not applied with mdc 0.26.0 ([9925308](https://github.com/stasson/vue-mdc-adapter/commit/9925308))


### Features

* **select:** implement foundation as per mdc 0.26.0 ([53c47db](https://github.com/stasson/vue-mdc-adapter/commit/53c47db))
* **textfield:** implement foundation as per mdc 0.26.0 ([426ceb9](https://github.com/stasson/vue-mdc-adapter/commit/426ceb9))



<a name="0.4.2"></a>
## [0.4.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.4.1...v0.4.2) (2017-11-26)



<a name="0.4.1"></a>
## [0.4.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.4.0...v0.4.1) (2017-11-25)


### Bug Fixes

* **demo:** fix iframes wrong imports ([f75773a](https://github.com/stasson/vue-mdc-adapter/commit/f75773a))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.3.0...v0.4.0) (2017-11-25)


### Features

* **dist:** refactor exports in order to simplify components imports ([fa8d049](https://github.com/stasson/vue-mdc-adapter/commit/fa8d049))


### BREAKING CHANGES

* **dist:** new naming convention VueMDC[Plugin], mdc[Component] and new distribution filename. check docs/getting-started.md for more



<a name="0.3.0"></a>
# [0.3.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.2.1...v0.3.0) (2017-11-18)


### Bug Fixes

* **textfield:** disable property is not reactive ([575f526](https://github.com/stasson/vue-mdc-adapter/commit/575f526)), closes [#111](https://github.com/stasson/vue-mdc-adapter/issues/111)
* **toolbar:** mdc-toolbar-menu name is confusing ([395a431](https://github.com/stasson/vue-mdc-adapter/commit/395a431)), closes [#113](https://github.com/stasson/vue-mdc-adapter/issues/113)
* **toolbar:** should be built as a single plugin [#114](https://github.com/stasson/vue-mdc-adapter/issues/114) ([b68b75d](https://github.com/stasson/vue-mdc-adapter/commit/b68b75d))


### BREAKING CHANGES

* **toolbar:** rename mdc-toolbar-menu to mdc-tollbar-menu-icon



<a name="0.2.1"></a>
## [0.2.1](https://github.com/stasson/vue-mdc-adapter/compare/v0.2.0...v0.2.1) (2017-11-14)


### Bug Fixes

* **package:** update material-components-web to version 0.25.0 ([1ed7f64](https://github.com/stasson/vue-mdc-adapter/commit/1ed7f64))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.8...v0.2.0) (2017-11-08)


### Bug Fixes

* **select:** option can not be selected once children slots have changed [#97](https://github.com/stasson/vue-mdc-adapter/issues/97) ([6742194](https://github.com/stasson/vue-mdc-adapter/commit/6742194))
* **typography:** component should not force adjust-margin [#101](https://github.com/stasson/vue-mdc-adapter/issues/101) ([ceaa6c1](https://github.com/stasson/vue-mdc-adapter/commit/ceaa6c1))
* **typography:** fix typography test.spec ([f91e121](https://github.com/stasson/vue-mdc-adapter/commit/f91e121))


### BREAKING CHANGES

* **typography:** typography components no longer force margin-adjust, it must be explicitly set.



<a name="0.1.8"></a>
## [0.1.8](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.6...v0.1.8) (2017-11-05)



<a name="0.1.7"></a>
## [0.1.7](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.6...v0.1.7) (2017-11-05)



<a name="0.1.6"></a>
## [0.1.6](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.5...v0.1.6) (2017-11-05)



<a name="0.1.5"></a>
## [0.1.5](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.4...v0.1.5) (2017-11-05)



<a name="0.1.4"></a>
## [0.1.4](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.3...v0.1.4) (2017-11-05)



<a name="0.1.3"></a>
## [0.1.3](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.1...v0.1.3) (2017-11-04)



<a name="0.1.2"></a>
## [0.1.2](https://github.com/stasson/vue-mdc-adapter/compare/v0.1.1...v0.1.2) (2017-11-04)


<a name="0.0.49"></a>
## [0.0.49](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.48...v0.0.49) (2017-11-01)


### Bug Fixes

* **checkbox:** fix missing adapter methods ([46fa83c](https://github.com/stasson/vue-mdc-adapter/commit/46fa83c))
* **dialog:** footer ripple missing ([46ac43a](https://github.com/stasson/vue-mdc-adapter/commit/46ac43a))
* **snackbar:** build failure ([359a609](https://github.com/stasson/vue-mdc-adapter/commit/359a609))
* **snackbar:** fix missing adapter api ([c6fb19e](https://github.com/stasson/vue-mdc-adapter/commit/c6fb19e))
* **test:** fix crashing test.spec ([e9e3594](https://github.com/stasson/vue-mdc-adapter/commit/e9e3594))
* **textfield:** adapter api mismatch ([d7311e5](https://github.com/stasson/vue-mdc-adapter/commit/d7311e5))



<a name="0.0.48"></a>
## [0.0.48](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.47...v0.0.48) (2017-10-27)


### Bug Fixes

* **demo:** fix router home links ([58ce57d](https://github.com/stasson/vue-mdc-adapter/commit/58ce57d))
* **drawer:** drawer has no --selected item style ([16cd196](https://github.com/stasson/vue-mdc-adapter/commit/16cd196))
* **drawer:** fix drawer behavior ([f446a11](https://github.com/stasson/vue-mdc-adapter/commit/f446a11)), closes [#92](https://github.com/stasson/vue-mdc-adapter/issues/92)
* **drawer:** fix responsive behavior of the drawer [#76](https://github.com/stasson/vue-mdc-adapter/issues/76) ([aff0a97](https://github.com/stasson/vue-mdc-adapter/commit/aff0a97))



<a name="0.0.47"></a>
## [0.0.47](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.46...v0.0.47) (2017-10-23)



<a name="0.0.46"></a>
## [0.0.46](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.45...v0.0.46) (2017-10-23)



<a name="0.0.45"></a>
## [0.0.45](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.44...v0.0.45) (2017-10-23)


### Bug Fixes

* **components:** fix missing 'name' option in the Vue components ([b31e66d](https://github.com/stasson/vue-mdc-adapter/commit/b31e66d))
* **layout-app:** allow main content to shrink ([ba21537](https://github.com/stasson/vue-mdc-adapter/commit/ba21537))
* **textfield:** label overlaps with content ([#86](https://github.com/stasson/vue-mdc-adapter/issues/86)) ([4964b91](https://github.com/stasson/vue-mdc-adapter/commit/4964b91))
* **util:** fix ripple for ssr ([809e3dd](https://github.com/stasson/vue-mdc-adapter/commit/809e3dd))


### Features

* **demo:** add readme and demos ([9334fa8](https://github.com/stasson/vue-mdc-adapter/commit/9334fa8))
* **demo:** publish new site ([45493a9](https://github.com/stasson/vue-mdc-adapter/commit/45493a9))
* **mdc-layout-app:** add new mdc-layout-app component ([e9fd92d](https://github.com/stasson/vue-mdc-adapter/commit/e9fd92d))



<a name="0.0.44"></a>
## [0.0.44](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.43...v0.0.44) (2017-10-06)


### Bug Fixes

* **button:** button click event is not being dispatched ([8d90920](https://github.com/stasson/vue-mdc-adapter/commit/8d90920))



<a name="0.0.43"></a>
## [0.0.43](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.42...v0.0.43) (2017-10-06)


### Features

* **textfield:** align textfield on mdc 0.22 ([05a93bc](https://github.com/stasson/vue-mdc-adapter/commit/05a93bc))



<a name="0.0.42"></a>
## [0.0.42](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.41...v0.0.42) (2017-10-04)


### Bug Fixes

* **ssr:** avoid fetching matches property on server ([#77](https://github.com/stasson/vue-mdc-adapter/issues/77)) ([e114841](https://github.com/stasson/vue-mdc-adapter/commit/e114841))


### Features

* **button:** add support for button links ([#79](https://github.com/stasson/vue-mdc-adapter/issues/79)) ([5b9f678](https://github.com/stasson/vue-mdc-adapter/commit/5b9f678))
* **util:** add custom element component ([65899c6](https://github.com/stasson/vue-mdc-adapter/commit/65899c6))



<a name="0.0.41"></a>
## [0.0.41](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.40...v0.0.41) (2017-09-30)


### Bug Fixes

* **button:** buttons accessibility isssue ([0a2613b](https://github.com/stasson/vue-mdc-adapter/commit/0a2613b)), closes [#72](https://github.com/stasson/vue-mdc-adapter/issues/72)
* **card:** action button should render a <button> tag ([30e7f25](https://github.com/stasson/vue-mdc-adapter/commit/30e7f25))
* **fab:** fix fab accessibility issue ([4322914](https://github.com/stasson/vue-mdc-adapter/commit/4322914))
* **infra:** fix release script ([f89c7a8](https://github.com/stasson/vue-mdc-adapter/commit/f89c7a8))


### Features

* **button:** add style for mdc-icon ([95fcbff](https://github.com/stasson/vue-mdc-adapter/commit/95fcbff))
* **icon:** add mdc-icon component ([f747ac1](https://github.com/stasson/vue-mdc-adapter/commit/f747ac1))
* **toolbar:** add support for custom icons ([d975a18](https://github.com/stasson/vue-mdc-adapter/commit/d975a18))


### BREAKING CHANGES

* **toolbar:** - mdc-toolbar-menu replaces mdc-toolbar-icon-menu
- use icon prop instead of slot to set the icon
* **fab:** use icon prop instead vs slot to set material icon content
* **button:** href abd icon props removed



<a name="0.0.40"></a>
## [0.0.40](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.39...v0.0.40) (2017-09-29)


### Features

* **changelog:** moving to angular git commit convention ([e07d5ab](https://github.com/stasson/vue-mdc-adapter/commit/e07d5ab)), closes [#71](https://github.com/stasson/vue-mdc-adapter/issues/71)



<a name="0.0.39"></a>
## [0.0.39](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.38...v0.0.39) (2017-09-19)

### BREAKING CHANGES

* **button:** remove button primary and accent prop as per MDC 0.21.0


<a name="0.0.38"></a>
## [0.0.38](https://github.com/stasson/vue-mdc-adapter/compare/v0.0.37...v0.0.38) (2017-09-10)


### BREAKING CHANGES

* **fab:** fab can not be disabled mdc@^0.20.0
