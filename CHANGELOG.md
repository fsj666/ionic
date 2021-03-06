<a name="4.0.0-beta.13"></a>
# [4.0.0-beta.13](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.12...v4.0.0-beta.13) (2018-10-14)


### Bug Fixes

* **all:** avoid using focus() since it conflicts with HTMLElement ([5560dcd](https://github.com/ionic-team/ionic/commit/5560dcd)), closes [#15810](https://github.com/ionic-team/ionic/issues/15810)
* **all:** disable animations in e2e tests ([9d109d6](https://github.com/ionic-team/ionic/commit/9d109d6))
* **all:** docs for all missing props ([a72fced](https://github.com/ionic-team/ionic/commit/a72fced))
* **angular:** add "main" to package.json as workaround for webstorm ([c57a7cc](https://github.com/ionic-team/ionic/commit/c57a7cc))
* **angular:** backButton event uses ionBackButton ([0337c7f](https://github.com/ionic-team/ionic/commit/0337c7f))
* **angular:** only bypass zone in high-rate events ([f63c0f5](https://github.com/ionic-team/ionic/commit/f63c0f5)), closes [#15765](https://github.com/ionic-team/ionic/issues/15765)
* **button:** use class instead of reflect ([e189cc6](https://github.com/ionic-team/ionic/commit/e189cc6)), closes [#15623](https://github.com/ionic-team/ionic/issues/15623)
* **card:** include card-header in current color ([b5e39c8](https://github.com/ionic-team/ionic/commit/b5e39c8))
* **card:** update currentColor to use contrast color ([a9a29f7](https://github.com/ionic-team/ionic/commit/a9a29f7))
* **card-header:** get color property working ([92514b3](https://github.com/ionic-team/ionic/commit/92514b3)), closes [#14723](https://github.com/ionic-team/ionic/issues/14723) [#14853](https://github.com/ionic-team/ionic/issues/14853)
* **col:** fix CSS is undefined error on IE11 ([#15882](https://github.com/ionic-team/ionic/issues/15882)) ([06a3028](https://github.com/ionic-team/ionic/commit/06a3028))
* **content:** iOS should not have scroll in desktop ([8cb1886](https://github.com/ionic-team/ionic/commit/8cb1886)), closes [#15858](https://github.com/ionic-team/ionic/issues/15858)
* **css:** avoid cleancss bug ([f87d4bf](https://github.com/ionic-team/ionic/commit/f87d4bf)), closes [#15807](https://github.com/ionic-team/ionic/issues/15807)
* **css:** remove selection color ([6b0d812](https://github.com/ionic-team/ionic/commit/6b0d812))
* **docs:** Fix commit link on CONTRIBUTING.md ([#15834](https://github.com/ionic-team/ionic/issues/15834)) ([fe0c3b4](https://github.com/ionic-team/ionic/commit/fe0c3b4))
* **fab-button:** add and document css properties ([098bd82](https://github.com/ionic-team/ionic/commit/098bd82)), closes [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **fab-button:** ripple-effect in safari ([844c33a](https://github.com/ionic-team/ionic/commit/844c33a)), closes [#15768](https://github.com/ionic-team/ionic/issues/15768)
* **hide/show:** fix show-when/hide-when ([fd01308](https://github.com/ionic-team/ionic/commit/fd01308)), closes [#15813](https://github.com/ionic-team/ionic/issues/15813)
* **infinite-scroll:** implements position="top" ([b4a73ad](https://github.com/ionic-team/ionic/commit/b4a73ad)), closes [#15481](https://github.com/ionic-team/ionic/issues/15481)
* **input:** add and document custom properties ([23df042](https://github.com/ionic-team/ionic/commit/23df042)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **input:** tabindex or tab in ion-input do not work with clearInput fix ([e916500](https://github.com/ionic-team/ionic/commit/e916500))
* **ion-datetime:** keep the model value consistently an ISO string ([#15907](https://github.com/ionic-team/ionic/issues/15907)) ([b46052b](https://github.com/ionic-team/ionic/commit/b46052b))
* **item:** add input highlight using an absolute div ([#15856](https://github.com/ionic-team/ionic/issues/15856)) ([f885f7d](https://github.com/ionic-team/ionic/commit/f885f7d)), closes [#14036](https://github.com/ionic-team/ionic/issues/14036) [#9639](https://github.com/ionic-team/ionic/issues/9639) [#14952](https://github.com/ionic-team/ionic/issues/14952) [#15690](https://github.com/ionic-team/ionic/issues/15690)
* **item:** detail context based in text color ([e51f1f3](https://github.com/ionic-team/ionic/commit/e51f1f3))
* **label:** add color variable, examples to test and document ([b485eba](https://github.com/ionic-team/ionic/commit/b485eba)), closes [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **list:** don't show inset lines for full line list ([6eae95a](https://github.com/ionic-team/ionic/commit/6eae95a))
* **menu:** menu registers itself before it's ready ([08beee3](https://github.com/ionic-team/ionic/commit/08beee3))
* **menu:** overlays can block menu closing ([11aa241](https://github.com/ionic-team/ionic/commit/11aa241)), closes [#15880](https://github.com/ionic-team/ionic/issues/15880)
* **menu:** wait until all menus are ready ([a5c2cc1](https://github.com/ionic-team/ionic/commit/a5c2cc1)), closes [#15727](https://github.com/ionic-team/ionic/issues/15727)
* **menu-button:** color ([386cf82](https://github.com/ionic-team/ionic/commit/386cf82)), closes [#15546](https://github.com/ionic-team/ionic/issues/15546) [#15545](https://github.com/ionic-team/ionic/issues/15545)
* **menu-button:** Not visible if toolbar has primary color ([#15847](https://github.com/ionic-team/ionic/issues/15847)) ([e2ea08b](https://github.com/ionic-team/ionic/commit/e2ea08b))
* **modal/popover:** lifecycle events ([19c449e](https://github.com/ionic-team/ionic/commit/19c449e)), closes [#15806](https://github.com/ionic-team/ionic/issues/15806)
* **picker:** stop animation when it's closed ([e81af2d](https://github.com/ionic-team/ionic/commit/e81af2d)), closes [#15854](https://github.com/ionic-team/ionic/issues/15854)
* **popover:** showBackdrop hides backdrop ([f00be0d](https://github.com/ionic-team/ionic/commit/f00be0d)), closes [#15878](https://github.com/ionic-team/ionic/issues/15878)
* **reorder-group:** delegate dom reordering ([5f65942](https://github.com/ionic-team/ionic/commit/5f65942)), closes [#15836](https://github.com/ionic-team/ionic/issues/15836)
* **slides:** disable autoplay by default ([db6ddb0](https://github.com/ionic-team/ionic/commit/db6ddb0)), closes [#15766](https://github.com/ionic-team/ionic/issues/15766)
* **tabbar:** css variables assigned to the host ([545db2e](https://github.com/ionic-team/ionic/commit/545db2e))
* **tabs:** badgeColor works again ([3d98587](https://github.com/ionic-team/ionic/commit/3d98587)), closes [#15559](https://github.com/ionic-team/ionic/issues/15559) [#14840](https://github.com/ionic-team/ionic/issues/14840)
* **tabs:** fix async deadlock ([905c7db](https://github.com/ionic-team/ionic/commit/905c7db))
* **title:** allow color to be set for title without attribute ([a9b3064](https://github.com/ionic-team/ionic/commit/a9b3064)), closes [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **toggle:** improve animation motion ([5330574](https://github.com/ionic-team/ionic/commit/5330574))


### Features

* **angular:** observer based api to override hardware back button ([6a5aec8](https://github.com/ionic-team/ionic/commit/6a5aec8)), closes [#15820](https://github.com/ionic-team/ionic/issues/15820)
* **menu:** add new lifeycle events ([64b52b5](https://github.com/ionic-team/ionic/commit/64b52b5))
* **nav:** animation is customizable ([24f3373](https://github.com/ionic-team/ionic/commit/24f3373)), closes [#15851](https://github.com/ionic-team/ionic/issues/15851)
* **overlays:** expose animation customization ([dc976cc](https://github.com/ionic-team/ionic/commit/dc976cc))
* initial vue support ([73cff0c](https://github.com/ionic-team/ionic/commit/73cff0c))


### Performance Improvements

* prevent unnecesary event listener changes ([a999c1f](https://github.com/ionic-team/ionic/commit/a999c1f))



<a name="4.0.0-beta.12"></a>
# [4.0.0-beta.12](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.11...v4.0.0-beta.12) (2018-09-26)


### Bug Fixes

* **action-sheet:** allow async button handler returned value ([3d3e6a4](https://github.com/ionic-team/ionic/commit/3d3e6a4))
* **alert:** check if value is null instead of truthy ([799f0d7](https://github.com/ionic-team/ionic/commit/799f0d7)), closes [#15420](https://github.com/ionic-team/ionic/issues/15420)
* **all:** gesture controller can block scrolling ([633360f](https://github.com/ionic-team/ionic/commit/633360f)), closes [#15725](https://github.com/ionic-team/ionic/issues/15725)
* **all:** lint errors ([f8eafa7](https://github.com/ionic-team/ionic/commit/f8eafa7))
* **all:** safe margins for fab, item-header, tabbar ([62eff0a](https://github.com/ionic-team/ionic/commit/62eff0a))
* **angular:** add event listener on window ([#15628](https://github.com/ionic-team/ionic/issues/15628)) ([7bd33a7](https://github.com/ionic-team/ionic/commit/7bd33a7))
* **angular:** import icons using webpack apis ([b71b36c](https://github.com/ionic-team/ionic/commit/b71b36c))
* **angular:** ionic/core is only a dep ([236d8a4](https://github.com/ionic-team/ionic/commit/236d8a4))
* **angular:** value is updates based in ionChange ([e18f8bf](https://github.com/ionic-team/ionic/commit/e18f8bf)), closes [#15722](https://github.com/ionic-team/ionic/issues/15722)
* **app:** statusTap and hardwareGB can be activated with config ([c048f9f](https://github.com/ionic-team/ionic/commit/c048f9f)), closes [#15617](https://github.com/ionic-team/ionic/issues/15617)
* **back-button:** add and document custom properties ([b3aebb8](https://github.com/ionic-team/ionic/commit/b3aebb8)), closes [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14853](https://github.com/ionic-team/ionic/issues/14853)
* **back-button:** default md color is inhered ([d0867b5](https://github.com/ionic-team/ionic/commit/d0867b5))
* **button:** default button width to auto to avoid inheriting ([bac49ca](https://github.com/ionic-team/ionic/commit/bac49ca)), closes [#15522](https://github.com/ionic-team/ionic/issues/15522)
* **button:** disable :hover on non supported devices ([#15705](https://github.com/ionic-team/ionic/issues/15705)) ([67eb661](https://github.com/ionic-team/ionic/commit/67eb661))
* **button:** disable pointer events in toolbar buttons ([d145cae](https://github.com/ionic-team/ionic/commit/d145cae)), closes [#15623](https://github.com/ionic-team/ionic/issues/15623)
* **buttons:** fix activated, position, animation ([9d6169a](https://github.com/ionic-team/ionic/commit/9d6169a))
* **color:** do not accept empty color ([ede5525](https://github.com/ionic-team/ionic/commit/ede5525)), closes [#15732](https://github.com/ionic-team/ionic/issues/15732)
* **content:** apply background to the inner scroll element ([f68c457](https://github.com/ionic-team/ionic/commit/f68c457)), closes [#15635](https://github.com/ionic-team/ionic/issues/15635)
* **content:** nested content ([5f5ba66](https://github.com/ionic-team/ionic/commit/5f5ba66)), closes [#15680](https://github.com/ionic-team/ionic/issues/15680)
* **datetime:** check for null instead of undefined ([407b147](https://github.com/ionic-team/ionic/commit/407b147)), closes [#15605](https://github.com/ionic-team/ionic/issues/15605)
* **datetime:** convert to shadow and fix broken styles ([fa77017](https://github.com/ionic-team/ionic/commit/fa77017)), closes [#15547](https://github.com/ionic-team/ionic/issues/15547) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **fab:** do not reset fab activated if it's false ([d619d8d](https://github.com/ionic-team/ionic/commit/d619d8d))
* **gestures:** change itemSliding gesture priority ([48927e6](https://github.com/ionic-team/ionic/commit/48927e6)), closes [#15608](https://github.com/ionic-team/ionic/issues/15608)
* **input:** fix text type for select change event ([694b6a8](https://github.com/ionic-team/ionic/commit/694b6a8))
* **item:** add the multiple inputs class to fix select/datetime in item ([1cd792e](https://github.com/ionic-team/ionic/commit/1cd792e)), closes [#15401](https://github.com/ionic-team/ionic/issues/15401)
* **item-divider:** add and document custom properties ([06cb138](https://github.com/ionic-team/ionic/commit/06cb138)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **item-option:** add and document custom properties ([2a040e0](https://github.com/ionic-team/ionic/commit/2a040e0)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14943](https://github.com/ionic-team/ionic/issues/14943)
* **menu:** crash when menu if forcedClosed ([22e15b4](https://github.com/ionic-team/ionic/commit/22e15b4))
* **menu:** opening a menu autocloses any opened ones ([8796f9f](https://github.com/ionic-team/ionic/commit/8796f9f))
* **menu-controller:** expose registerAnimation ([29d00da](https://github.com/ionic-team/ionic/commit/29d00da)), closes [#15701](https://github.com/ionic-team/ionic/issues/15701)
* **overlay:** register backbutton handler only when needed ([#15615](https://github.com/ionic-team/ionic/issues/15615)) ([b2b5d93](https://github.com/ionic-team/ionic/commit/b2b5d93)), closes [#15601](https://github.com/ionic-team/ionic/issues/15601)
* **platform:** using desktop instead of window ([c8de84d](https://github.com/ionic-team/ionic/commit/c8de84d))
* add safe area cutouts ([#15750](https://github.com/ionic-team/ionic/issues/15750)) ([a3c85ae](https://github.com/ionic-team/ionic/commit/a3c85ae))
* **radio:** add css variables to make it customizable ([9ec8e74](https://github.com/ionic-team/ionic/commit/9ec8e74)), closes [#15729](https://github.com/ionic-team/ionic/issues/15729)
* **select:** add position styles to work as standalone ([224b4f8](https://github.com/ionic-team/ionic/commit/224b4f8))
* **select:** placeholder can be reset if value = null ([602f668](https://github.com/ionic-team/ionic/commit/602f668))
* **select:** show placeholder when multiple is empty ([29862e8](https://github.com/ionic-team/ionic/commit/29862e8))
* **select-popover:** add scoped to apply proper styles to list ([fd1b636](https://github.com/ionic-team/ionic/commit/fd1b636))
* **slides:** add back zoom plugin for swiper ([6890ecc](https://github.com/ionic-team/ionic/commit/6890ecc)), closes [#15676](https://github.com/ionic-team/ionic/issues/15676)
* **slides:** fix mutable options ([681981f](https://github.com/ionic-team/ionic/commit/681981f))
* **tap-click:** prevent activated while scrolling ([7f38d37](https://github.com/ionic-team/ionic/commit/7f38d37)), closes [#15752](https://github.com/ionic-team/ionic/issues/15752)
* **toast:** button color is contrast ([f65ec10](https://github.com/ionic-team/ionic/commit/f65ec10)), closes [#15737](https://github.com/ionic-team/ionic/issues/15737)


### Features

* **animation:** ability to disable animations w/ querystring ([734b222](https://github.com/ionic-team/ionic/commit/734b222))
* **app:** adds _forceStatusbarPadding for ionic lab ([0379977](https://github.com/ionic-team/ionic/commit/0379977))
* **ripple:** ability to disable ripple effect w/ querystring ([efca0ae](https://github.com/ionic-team/ionic/commit/efca0ae))
* **screenshot:** update to use stencil e2e screenshot testing ([43b9045](https://github.com/ionic-team/ionic/commit/43b9045))


### Reverts

* **content:** block scrolling in ion-content ([9badb08](https://github.com/ionic-team/ionic/commit/9badb08))



<a name="4.0.0-beta.11"></a>
# [4.0.0-beta.11](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.10...v4.0.0-beta.11) (2018-09-14)


### Bug Fixes

* **slides:** swiper must be a vendor ([3435473](https://github.com/ionic-team/ionic/commit/3435473))



<a name="4.0.0-beta.10"></a>
# [4.0.0-beta.10](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.9...v4.0.0-beta.10) (2018-09-14)


### Bug Fixes

* **animation:** always call onFinish() ([c23c5a4](https://github.com/ionic-team/ionic/commit/c23c5a4))
* **button:** vanilla color is usable ([b8b9b83](https://github.com/ionic-team/ionic/commit/b8b9b83))
* **segment:** unselected color ([b9e42eb](https://github.com/ionic-team/ionic/commit/b9e42eb))
* **slides:** swiper is not required as dependency ([29f324b](https://github.com/ionic-team/ionic/commit/29f324b))



<a name="4.0.0-beta.9"></a>
# [4.0.0-beta.9](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.7...v4.0.0-beta.9) (2018-09-14)


### Bug Fixes

* **anchor:** make it activatable ([6c62e6c](https://github.com/ionic-team/ionic/commit/6c62e6c))
* **angular:** only append the component when the parent element is not the container element ([6d6f70c](https://github.com/ionic-team/ionic/commit/6d6f70c)), closes [#14737](https://github.com/ionic-team/ionic/issues/14737)
* **back-button:** subscribe to body ([37c9be7](https://github.com/ionic-team/ionic/commit/37c9be7))
* **button:** add custom properties and remove --ion-color overrides ([#15463](https://github.com/ionic-team/ionic/issues/15463)) ([3af4361](https://github.com/ionic-team/ionic/commit/3af4361)), closes [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **core:** matchBreakpoint will return true if breakPoint is empty string ([#15498](https://github.com/ionic-team/ionic/issues/15498)) ([b362b0a](https://github.com/ionic-team/ionic/commit/b362b0a)), closes [#15495](https://github.com/ionic-team/ionic/issues/15495)
* **esm:** reorganiza exports ([bb19243](https://github.com/ionic-team/ionic/commit/bb19243))
* **fab-button:** add routerDirection ([2398634](https://github.com/ionic-team/ionic/commit/2398634)), closes [#15551](https://github.com/ionic-team/ionic/issues/15551)
* **input:** value might be null/undefined ([83543b7](https://github.com/ionic-team/ionic/commit/83543b7))
* **item:** update hostContext to use ion-item element ([21d1f2e](https://github.com/ionic-team/ionic/commit/21d1f2e))
* **item-option:** add activated and ripple to button ([78e2a0a](https://github.com/ionic-team/ionic/commit/78e2a0a)), closes [#14943](https://github.com/ionic-team/ionic/issues/14943)
* **item-option:** enable ripple-effect ([428a5da](https://github.com/ionic-team/ionic/commit/428a5da))
* **item-sliding:** make sure options are ready ([7f59f91](https://github.com/ionic-team/ionic/commit/7f59f91))
* **list-header:** add and document custom properties ([5ccc1fd](https://github.com/ionic-team/ionic/commit/5ccc1fd)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **menu:** ios styles ([281f9a3](https://github.com/ionic-team/ionic/commit/281f9a3))
* **nav:** matches() function ([9420b88](https://github.com/ionic-team/ionic/commit/9420b88))
* **overlay:** animation can be interrupted ([ca58664](https://github.com/ionic-team/ionic/commit/ca58664)), closes [#15506](https://github.com/ionic-team/ionic/issues/15506)
* **overlay:** only register backButton listener once ([75c2d74](https://github.com/ionic-team/ionic/commit/75c2d74))
* **popover:** content sizing, scoped css ([51d4e08](https://github.com/ionic-team/ionic/commit/51d4e08)), closes [#15237](https://github.com/ionic-team/ionic/issues/15237) [#15589](https://github.com/ionic-team/ionic/issues/15589) [#15331](https://github.com/ionic-team/ionic/issues/15331)
* **popover:** remove unneeded code ([b26c017](https://github.com/ionic-team/ionic/commit/b26c017))
* **radio:** add and document custom properties ([0f9a7b4](https://github.com/ionic-team/ionic/commit/0f9a7b4)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **range:** update range ratio when new min/max are passed ([#15512](https://github.com/ionic-team/ionic/issues/15512)) ([f62601f](https://github.com/ionic-team/ionic/commit/f62601f)), closes [#15511](https://github.com/ionic-team/ionic/issues/15511)
* **searchbar:** add and document custom properties ([7f57e02](https://github.com/ionic-team/ionic/commit/7f57e02)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **searchbar:** inherit color from color toolbar ([3042f57](https://github.com/ionic-team/ionic/commit/3042f57))
* **searchbar:** ionCancel event ([20a7599](https://github.com/ionic-team/ionic/commit/20a7599)), closes [#15476](https://github.com/ionic-team/ionic/issues/15476)
* **segment:** fix css var + host-context() ([49ab065](https://github.com/ionic-team/ionic/commit/49ab065))
* **slides:** correct order of parameters ([6442dfc](https://github.com/ionic-team/ionic/commit/6442dfc)), closes [#15407](https://github.com/ionic-team/ionic/issues/15407)
* **slides:** Methods wait for execution until swiper is initialized ([#15576](https://github.com/ionic-team/ionic/issues/15576)) ([ea01900](https://github.com/ionic-team/ionic/commit/ea01900))
* **slides:** Update swiperOptions default to match version 4 of Swiper ([#15578](https://github.com/ionic-team/ionic/issues/15578)) ([db35af2](https://github.com/ionic-team/ionic/commit/db35af2))
* **slides:** Updated lockSwipes methods to match the new swiper.js API ([#15469](https://github.com/ionic-team/ionic/issues/15469)) ([efb99cb](https://github.com/ionic-team/ionic/commit/efb99cb))
* **sliding-item:** swipe event ([127da1a](https://github.com/ionic-team/ionic/commit/127da1a))
* **test:** treeshake check runs last ([b56f136](https://github.com/ionic-team/ionic/commit/b56f136))
* **test:** workaround for nav tests ([a4b1179](https://github.com/ionic-team/ionic/commit/a4b1179))
* **toast:** adds role timeout and cancel ([2f2a255](https://github.com/ionic-team/ionic/commit/2f2a255)), closes [#15477](https://github.com/ionic-team/ionic/issues/15477)
* **toast:** render on top ([ac42180](https://github.com/ionic-team/ionic/commit/ac42180))
* **toggle:** empty hidden input value when not checked ([1f19862](https://github.com/ionic-team/ionic/commit/1f19862))
* handle failure in hardware back button ([6da765b](https://github.com/ionic-team/ionic/commit/6da765b))
* remove argument-less catch() ([ff919de](https://github.com/ionic-team/ionic/commit/ff919de))


### Features

* **angular:** integrate back-button with ng router ([1bcca01](https://github.com/ionic-team/ionic/commit/1bcca01))
* **app:** hardware back button support ([dfac9dc](https://github.com/ionic-team/ionic/commit/dfac9dc))
* **overlays:** close overlay with back-button ([4ccbefa](https://github.com/ionic-team/ionic/commit/4ccbefa))
* **router:** add support for relative paths ([b28aeab](https://github.com/ionic-team/ionic/commit/b28aeab)), closes [#15499](https://github.com/ionic-team/ionic/issues/15499)
* **virtual-scroller:** add <template> support ([d40d0a7](https://github.com/ionic-team/ionic/commit/d40d0a7))


### Performance Improvements

* **router:** prevent initializaing page twice ([3dd9604](https://github.com/ionic-team/ionic/commit/3dd9604))
* **slides:** tree-shake dependency ([9d3a259](https://github.com/ionic-team/ionic/commit/9d3a259))



<a name="4.0.0-beta.8"></a>
# [4.0.0-beta.8](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.7...v4.0.0-beta.8) (2018-09-06)


### Bug Fixes

* **button:** add custom properties and remove --ion-color overrides ([#15463](https://github.com/ionic-team/ionic/issues/15463)) ([3af4361](https://github.com/ionic-team/ionic/commit/3af4361)), closes [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **menu:** ios styles ([281f9a3](https://github.com/ionic-team/ionic/commit/281f9a3))
* **radio:** add and document custom properties ([0f9a7b4](https://github.com/ionic-team/ionic/commit/0f9a7b4)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **searchbar:** inherit color from color toolbar ([3042f57](https://github.com/ionic-team/ionic/commit/3042f57))
* **slides:** correct order of parameters ([6442dfc](https://github.com/ionic-team/ionic/commit/6442dfc)), closes [#15407](https://github.com/ionic-team/ionic/issues/15407)
* **test:** treeshake check runs last ([b56f136](https://github.com/ionic-team/ionic/commit/b56f136))
* **test:** workaround for nav tests ([a4b1179](https://github.com/ionic-team/ionic/commit/a4b1179))
* **toggle:** empty hidden input value when not checked ([1f19862](https://github.com/ionic-team/ionic/commit/1f19862))


### Features

* **angular:** integrate back-button with ng router ([1bcca01](https://github.com/ionic-team/ionic/commit/1bcca01))
* **app:** hardware back button support ([dfac9dc](https://github.com/ionic-team/ionic/commit/dfac9dc))
* **overlays:** close overlay with back-button ([4ccbefa](https://github.com/ionic-team/ionic/commit/4ccbefa))
* **virtual-scroller:** add <template> support ([d40d0a7](https://github.com/ionic-team/ionic/commit/d40d0a7))



<a name="4.0.0-beta.7"></a>
# [4.0.0-beta.7](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.6...v4.0.0-beta.7) (2018-08-30)


### Bug Fixes

* **list:** add closeSlidingItems() ([81fbbb8](https://github.com/ionic-team/ionic/commit/81fbbb8)), closes [#15378](https://github.com/ionic-team/ionic/issues/15378)
* **menu:** await animation check ([f00db59](https://github.com/ionic-team/ionic/commit/f00db59)), closes [#15377](https://github.com/ionic-team/ionic/issues/15377)
* **range:** add and document custom properties ([cf35445](https://github.com/ionic-team/ionic/commit/cf35445)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **slides:** isEnd() returns a boolean ([771c517](https://github.com/ionic-team/ionic/commit/771c517)), closes [#15376](https://github.com/ionic-team/ionic/issues/15376)



<a name="4.0.0-beta.6"></a>
# [4.0.0-beta.6](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.5...v4.0.0-beta.6) (2018-08-29)

### Breaking Changes

- All methods of all ionic components return a promise.
- `colors.css` has been renamed to `core.css`, the global stylesheet needs to be updated:

#### Stencil

```diff
+ @import "~@ionic/core/css/core.css";
  @import "~@ionic/core/css/normalize.css";
  @import "~@ionic/core/css/structure.css";
  @import "~@ionic/core/css/typography.css";
- @import "~@ionic/core/css/colors.css";

  @import "~@ionic/core/css/padding.css";
  @import "~@ionic/core/css/float-elements.css";
  @import "~@ionic/core/css/text-alignment.css";
  @import "~@ionic/core/css/text-transformation.css";
  @import "~@ionic/core/css/flex-utils.css";
```

#### Angular

```diff
+ @import "~@ionic/angular/css/core.css";
  @import "~@ionic/angular/css/normalize.css";
  @import "~@ionic/angular/css/structure.css";
  @import "~@ionic/angular/css/typography.css";
- @import "~@ionic/angular/css/colors.css";

  @import "~@ionic/angular/css/padding.css";
  @import "~@ionic/angular/css/float-elements.css";
  @import "~@ionic/angular/css/text-alignment.css";
  @import "~@ionic/angular/css/text-transformation.css";
  @import "~@ionic/angular/css/flex-utils.css";
```

### Bug Fixes

* **alert:** header is not mandatory ([1f71f76](https://github.com/ionic-team/ionic/commit/1f71f76))
* **alert:** name is non-null ([2268346](https://github.com/ionic-team/ionic/commit/2268346))
* **alert:** type and name props are optional ([#14815](https://github.com/ionic-team/ionic/issues/14815)) ([99a2925](https://github.com/ionic-team/ionic/commit/99a2925))
* **angular:** NavController signatures ([6fdeb31](https://github.com/ionic-team/ionic/commit/6fdeb31)), closes [#15353](https://github.com/ionic-team/ionic/issues/15353)
* **angular:** overlay not found ([8dfc52f](https://github.com/ionic-team/ionic/commit/8dfc52f)), closes [#15349](https://github.com/ionic-team/ionic/issues/15349)
* **angular:** platform does not crash ([82f9fd4](https://github.com/ionic-team/ionic/commit/82f9fd4)), closes [#15348](https://github.com/ionic-team/ionic/issues/15348)
* **angular:** virtual-scroll ([f9bf5c0](https://github.com/ionic-team/ionic/commit/f9bf5c0)), closes [#15355](https://github.com/ionic-team/ionic/issues/15355)
* **css:** add core.css ([#15220](https://github.com/ionic-team/ionic/issues/15220)) ([096d9a7](https://github.com/ionic-team/ionic/commit/096d9a7)), closes [#15170](https://github.com/ionic-team/ionic/issues/15170)
* **datetime:** fix year to allow current and max year ([f30ae88](https://github.com/ionic-team/ionic/commit/f30ae88)), closes [#14895](https://github.com/ionic-team/ionic/issues/14895)
* **grid:** working check for CSS custom variables in Safari ([#15228](https://github.com/ionic-team/ionic/issues/15228)) ([baefda3](https://github.com/ionic-team/ionic/commit/baefda3))
* **ion-reorder-group:** adds ionItemReorder event  ([7fc170c](https://github.com/ionic-team/ionic/commit/7fc170c)), closes [#14640](https://github.com/ionic-team/ionic/issues/14640)
* **overlay:** overlay is not hidden ([89ba55d](https://github.com/ionic-team/ionic/commit/89ba55d))
* **overlay:** overlays are hidden until presented ([ba428cd](https://github.com/ionic-team/ionic/commit/ba428cd)), closes [#15345](https://github.com/ionic-team/ionic/issues/15345)
* **overlays:** expose mode, id, keyboardClose ([cc960c3](https://github.com/ionic-team/ionic/commit/cc960c3)), closes [#15366](https://github.com/ionic-team/ionic/issues/15366)
* **radio-group:** accept any value ([16452b2](https://github.com/ionic-team/ionic/commit/16452b2)), closes [#15334](https://github.com/ionic-team/ionic/issues/15334)
* **segment:** set --color-checked in md color toolbar ([5d32115](https://github.com/ionic-team/ionic/commit/5d32115)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **toast:** add position middle ([25479e4](https://github.com/ionic-team/ionic/commit/25479e4))



<a name="4.0.0-beta.5"></a>
# [4.0.0-beta.5](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.4...v4.0.0-beta.5) (2018-08-27)

### Bug Fixes

- Ionic/angular compiler error

### Breaking Changes

#### NavController

Changes are required to accommodate some new useful routing APIs and match the ng router ones closely:

```
goForward() -> navigateForward()
goBack() -> navigateBack()
goRoot() -> navigateRoot()
```

#### Dependencies

The following dependencies need to be updated to resolve build errors

- Update Angular to 6.1 or higher
  - [Angular changelog](https://github.com/angular/angular/blob/master/CHANGELOG.md#610-2018-07-25)
- Update Typescript to 2.9.2
  - `"typescript": "~2.9.2"`


<a name="4.0.0-beta.4"></a>
# [4.0.0-beta.4](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.3...v4.0.0-beta.4) (2018-08-27)


### Bug Fixes

* **alert:** remove unneeded warning ([8447f28](https://github.com/ionic-team/ionic/commit/8447f28))
* **all:** add customization of font-style ([c957ea6](https://github.com/ionic-team/ionic/commit/c957ea6))
* **angular:** back navigation and back-button play better ([#15293](https://github.com/ionic-team/ionic/issues/15293)) ([9ddfb1b](https://github.com/ionic-team/ionic/commit/9ddfb1b)), closes [#15290](https://github.com/ionic-team/ionic/issues/15290)
* **angular:** expose router.navigate() ([7aa4f13](https://github.com/ionic-team/ionic/commit/7aa4f13)), closes [#15332](https://github.com/ionic-team/ionic/issues/15332)
* **app:** --ion-safe-area-right typo ([77ca2bd](https://github.com/ionic-team/ionic/commit/77ca2bd))
* **app:** listen statusTap event ([dc82675](https://github.com/ionic-team/ionic/commit/dc82675))
* **app:** statusbarPadding config is a boolean ([b387de4](https://github.com/ionic-team/ionic/commit/b387de4))
* **build:** do not export in component modules ([da2dc7b](https://github.com/ionic-team/ionic/commit/da2dc7b))
* **buttons:** margin between buttons ([359c47f](https://github.com/ionic-team/ionic/commit/359c47f))
* **card:** remove calculated width to work with dynamic margin ([059d365](https://github.com/ionic-team/ionic/commit/059d365)), closes [#15223](https://github.com/ionic-team/ionic/issues/15223)
* **chip:** add and document custom properties ([07e99a1](https://github.com/ionic-team/ionic/commit/07e99a1)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14853](https://github.com/ionic-team/ionic/issues/14853) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **config:** scrollAssist boolean definition ([#15203](https://github.com/ionic-team/ionic/issues/15203)) ([2af72fa](https://github.com/ionic-team/ionic/commit/2af72fa))
* **config:** using sessionStorage is not safe ([091b433](https://github.com/ionic-team/ionic/commit/091b433))
* **content:** document and add custom properties ([0372aec](https://github.com/ionic-team/ionic/commit/0372aec)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14853](https://github.com/ionic-team/ionic/issues/14853)
* **content:** fix scroll events ([962578e](https://github.com/ionic-team/ionic/commit/962578e)), closes [#15244](https://github.com/ionic-team/ionic/issues/15244)
* **content:** scrollToPoint reliability ([e0f1259](https://github.com/ionic-team/ionic/commit/e0f1259)), closes [#15257](https://github.com/ionic-team/ionic/issues/15257)
* **datetime:** allow values to be zero ([#14480](https://github.com/ionic-team/ionic/issues/14480)) ([e0b8e24](https://github.com/ionic-team/ionic/commit/e0b8e24))
* **docs:** add missed menu title in the list ([#15300](https://github.com/ionic-team/ionic/issues/15300)) ([5f3c7cd](https://github.com/ionic-team/ionic/commit/5f3c7cd))
* **docs:** use shape property to get round buttons ([#15321](https://github.com/ionic-team/ionic/issues/15321)) ([d4c812f](https://github.com/ionic-team/ionic/commit/d4c812f))
* **docs:** use shape property to get round buttons ([#15322](https://github.com/ionic-team/ionic/issues/15322)) ([5c6fe45](https://github.com/ionic-team/ionic/commit/5c6fe45))
* **hide-when:** mode is a reserved property ([c446d1b](https://github.com/ionic-team/ionic/commit/c446d1b))
* **img:** add object-fit to the host to avoid skewing the inner img ([2e94227](https://github.com/ionic-team/ionic/commit/2e94227))
* **infinite-scroll:** remove unused method ([926758e](https://github.com/ionic-team/ionic/commit/926758e))
* **input:** clearInput works in device ([ac96705](https://github.com/ionic-team/ionic/commit/ac96705)), closes [#15319](https://github.com/ionic-team/ionic/issues/15319)
* **menu:** do not override --ion-color-base ([a890828](https://github.com/ionic-team/ionic/commit/a890828))
* **modal:** make sure content is ready ([2c8bc04](https://github.com/ionic-team/ionic/commit/2c8bc04)), closes [#14969](https://github.com/ionic-team/ionic/issues/14969)
* **nav:** remove nav-decor once transition finished ([b8a87fb](https://github.com/ionic-team/ionic/commit/b8a87fb)), closes [#15121](https://github.com/ionic-team/ionic/issues/15121)
* **note:** do not overide --ion-color-base ([5f90dbf](https://github.com/ionic-team/ionic/commit/5f90dbf))
* **overlay:** expose "animated" API ([8b768fb](https://github.com/ionic-team/ionic/commit/8b768fb)), closes [#14775](https://github.com/ionic-team/ionic/issues/14775)
* **overlays:** dismiss last overlay ([c1c5102](https://github.com/ionic-team/ionic/commit/c1c5102))
* **overlays:** esc button works closed top overlays ([c567a82](https://github.com/ionic-team/ionic/commit/c567a82)), closes [#14662](https://github.com/ionic-team/ionic/issues/14662)
* **picker:** tune scrolling speed ([bd75bf4](https://github.com/ionic-team/ionic/commit/bd75bf4))
* **platform:** better detect platforms + css API ([3ffa3cd](https://github.com/ionic-team/ionic/commit/3ffa3cd)), closes [#15165](https://github.com/ionic-team/ionic/issues/15165) [#15116](https://github.com/ionic-team/ionic/issues/15116)
* **popover:** make sure content is ready ([8bf60e7](https://github.com/ionic-team/ionic/commit/8bf60e7))
* **popover:** they should not below other overlays ([d83e7f8](https://github.com/ionic-team/ionic/commit/d83e7f8)), closes [#14662](https://github.com/ionic-team/ionic/issues/14662)
* **refresher:** tune threshold ([d129f62](https://github.com/ionic-team/ionic/commit/d129f62)), closes [#15233](https://github.com/ionic-team/ionic/issues/15233)
* **ripple-effect:** add and document custom properties ([37a149c](https://github.com/ionic-team/ionic/commit/37a149c)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **segment:** add and document custom properties ([08c6c97](https://github.com/ionic-team/ionic/commit/08c6c97)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808) [#14854](https://github.com/ionic-team/ionic/issues/14854)
* **select:** add and document custom properties ([88613ff](https://github.com/ionic-team/ionic/commit/88613ff)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **select:** random type in generated.d.ts ([11edc49](https://github.com/ionic-team/ionic/commit/11edc49))
* **select:** support any kind of value ([151c58e](https://github.com/ionic-team/ionic/commit/151c58e)), closes [#15200](https://github.com/ionic-team/ionic/issues/15200)
* **skeleton-text:** add and document custom properties ([b213500](https://github.com/ionic-team/ionic/commit/b213500)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **slides:** document custom properties ([ecf1eb8](https://github.com/ionic-team/ionic/commit/ecf1eb8)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **split-pane:** add and document custom properties ([9104850](https://github.com/ionic-team/ionic/commit/9104850)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **textarea:** remove autocomplete prop ([5989f15](https://github.com/ionic-team/ionic/commit/5989f15))
* **title:** mode is inherited ([94ea0a6](https://github.com/ionic-team/ionic/commit/94ea0a6)), closes [#15187](https://github.com/ionic-team/ionic/issues/15187)
* **toggle:** cursor: pointer in desktop ([86acb8c](https://github.com/ionic-team/ionic/commit/86acb8c))
* **toolbar:** add position relative to host for toolbar background ([ac2db9f](https://github.com/ionic-team/ionic/commit/ac2db9f)), closes [#15193](https://github.com/ionic-team/ionic/issues/15193)
* **transition:** cleanup transition ([70a38ac](https://github.com/ionic-team/ionic/commit/70a38ac)), closes [#15317](https://github.com/ionic-team/ionic/issues/15317)
* **virtual-scroll:** update VS when items change ([3adfb98](https://github.com/ionic-team/ionic/commit/3adfb98))


### Features

* **all:** strong typed ComponentProps ([57d2375](https://github.com/ionic-team/ionic/commit/57d2375))
* **inputs:** add focus() method ([c66a34a](https://github.com/ionic-team/ionic/commit/c66a34a)), closes [#15266](https://github.com/ionic-team/ionic/issues/15266) [#15268](https://github.com/ionic-team/ionic/issues/15268)
* **platform:** add capacitor ([7356ba5](https://github.com/ionic-team/ionic/commit/7356ba5))


### Performance Improvements

* **overlay:** prevent layout thrashing ([ed5c8eb](https://github.com/ionic-team/ionic/commit/ed5c8eb))
* **ripple-effect:** using requestIdleCallback ([ea1c3d4](https://github.com/ionic-team/ionic/commit/ea1c3d4))


<a name="4.0.0-beta.3"></a>
# [4.0.0-beta.3](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.2...v4.0.0-beta.3) (2018-08-16)


### Bug Fixes

* **all:** improve text customization ([6e3e07b](https://github.com/ionic-team/ionic/commit/6e3e07b))
* **all:** safe-area using css variables ([aa23d08](https://github.com/ionic-team/ionic/commit/aa23d08))
* **all:** user-select for desktop ([2d70ee4](https://github.com/ionic-team/ionic/commit/2d70ee4))
* **anchor:** add custom properties and make sure color works properly ([8fef263](https://github.com/ionic-team/ionic/commit/8fef263)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **angular:** add ion-backdrop ([89e8256](https://github.com/ionic-team/ionic/commit/89e8256)), closes [#14971](https://github.com/ionic-team/ionic/issues/14971)
* **angular:** save internal data ([f84bb76](https://github.com/ionic-team/ionic/commit/f84bb76)), closes [#14888](https://github.com/ionic-team/ionic/issues/14888) [#14885](https://github.com/ionic-team/ionic/issues/14885) [#15054](https://github.com/ionic-team/ionic/issues/15054) [#15050](https://github.com/ionic-team/ionic/issues/15050)
* **avatar:** document and add custom properties ([6738ab7](https://github.com/ionic-team/ionic/commit/6738ab7)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **badge:** add custom properties and make sure color works properly ([9beca98](https://github.com/ionic-team/ionic/commit/9beca98)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **card:** add custom CSS properties and remove css overrides on item ([5ed2201](https://github.com/ionic-team/ionic/commit/5ed2201)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808) [#9198](https://github.com/ionic-team/ionic/issues/9198) [#12646](https://github.com/ionic-team/ionic/issues/12646)
* **card-subtitle:** add and document custom CSS properties ([7050039](https://github.com/ionic-team/ionic/commit/7050039)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **card-title:** add and document custom CSS properties ([1ad9818](https://github.com/ionic-team/ionic/commit/1ad9818)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **checkbox:** document and add custom CSS properties ([3e3cc6c](https://github.com/ionic-team/ionic/commit/3e3cc6c)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850) [#14808](https://github.com/ionic-team/ionic/issues/14808)
* **config:** add persistance mode ([db0049f](https://github.com/ionic-team/ionic/commit/db0049f)), closes [#15102](https://github.com/ionic-team/ionic/issues/15102)
* **config:** persistConfig ([1e1964d](https://github.com/ionic-team/ionic/commit/1e1964d))
* **content:** overflow-behavior: contain ([6173479](https://github.com/ionic-team/ionic/commit/6173479))
* **content:** scrolling Y ([01323ac](https://github.com/ionic-team/ionic/commit/01323ac))
* **content:** scrollToTop ([695abcf](https://github.com/ionic-team/ionic/commit/695abcf))
* **css:** --ion-item-background > --ion-item-background-color ([#15101](https://github.com/ionic-team/ionic/issues/15101)) ([e3010e1](https://github.com/ionic-team/ionic/commit/e3010e1))
* **datetime:** add open() method ([f032769](https://github.com/ionic-team/ionic/commit/f032769)), closes [#14923](https://github.com/ionic-team/ionic/issues/14923)
* **docs:** replace ion-navbar with ion-toolbar ([#15126](https://github.com/ionic-team/ionic/issues/15126)) ([0219309](https://github.com/ionic-team/ionic/commit/0219309))
* **fab-button:** sets pointer-events none when disabled ([04d33e5](https://github.com/ionic-team/ionic/commit/04d33e5)), closes [#15129](https://github.com/ionic-team/ionic/issues/15129) [#15120](https://github.com/ionic-team/ionic/issues/15120)
* **input:** event interfaces ([2e7d355](https://github.com/ionic-team/ionic/commit/2e7d355))
* **menu:** dismiss when clicking outside ([288eeb5](https://github.com/ionic-team/ionic/commit/288eeb5)), closes [#15096](https://github.com/ionic-team/ionic/issues/15096)
* **picker:** allow 0 as the selectedIndex ([d19061c](https://github.com/ionic-team/ionic/commit/d19061c)), closes [#14563](https://github.com/ionic-team/ionic/issues/14563)
* **range:** adds css var ([3ab835c](https://github.com/ionic-team/ionic/commit/3ab835c)), closes [#15064](https://github.com/ionic-team/ionic/issues/15064)
* **router:** transition race condition ([50ad1e7](https://github.com/ionic-team/ionic/commit/50ad1e7)), closes [#14873](https://github.com/ionic-team/ionic/issues/14873) [#15090](https://github.com/ionic-team/ionic/issues/15090)
* **segment:** center align text ([154b70e](https://github.com/ionic-team/ionic/commit/154b70e))
* **segment-button:** add and document custom properties ([85ffe01](https://github.com/ionic-team/ionic/commit/85ffe01)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **select:** apply proper styles for stacked/floating selects ([42ca99d](https://github.com/ionic-team/ionic/commit/42ca99d)), closes [#15140](https://github.com/ionic-team/ionic/issues/15140) [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **spinner:** add and document custom properties ([da6df2a](https://github.com/ionic-team/ionic/commit/da6df2a)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **split-pane:** disabled prop is dynamic ([149039b](https://github.com/ionic-team/ionic/commit/149039b)), closes [#14959](https://github.com/ionic-team/ionic/issues/14959)
* **tabbar:** fix highlight bar ([39104cb](https://github.com/ionic-team/ionic/commit/39104cb))
* **tabs:** get the tabbar layout working with shadow DOM ([#15113](https://github.com/ionic-team/ionic/issues/15113)) ([575c5eb](https://github.com/ionic-team/ionic/commit/575c5eb)), closes [#14611](https://github.com/ionic-team/ionic/issues/14611)
* **tap-click:** nested buttons get activated first ([03da98e](https://github.com/ionic-team/ionic/commit/03da98e))
* **tap-click:** works inside shadow-dom ([0dc70f7](https://github.com/ionic-team/ionic/commit/0dc70f7)), closes [#15128](https://github.com/ionic-team/ionic/issues/15128)
* **textarea:** add and document custom properties ([5dfcd47](https://github.com/ionic-team/ionic/commit/5dfcd47))
* **textarea:** add ion color classes ([5627811](https://github.com/ionic-team/ionic/commit/5627811))
* **thumbnail:** add and document custom properties ([c88e1ad](https://github.com/ionic-team/ionic/commit/c88e1ad)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **toast:** add and document custom properties ([5f6f6a1](https://github.com/ionic-team/ionic/commit/5f6f6a1)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **toast:** statusbarPadding ([3da1bf4](https://github.com/ionic-team/ionic/commit/3da1bf4))
* **toggle:** add and document custom properties ([773c2c2](https://github.com/ionic-team/ionic/commit/773c2c2)), closes [#14850](https://github.com/ionic-team/ionic/issues/14850)
* **toolbar:** add and document custom properties ([dd114ff](https://github.com/ionic-team/ionic/commit/dd114ff))
* **virtual-scroll:** fix viewportOffset calculation ([b7e741a](https://github.com/ionic-team/ionic/commit/b7e741a)), closes [#14963](https://github.com/ionic-team/ionic/issues/14963)
* **virtual-scroll:** use FunctionalComponent for JSX integration ([b53ce4b](https://github.com/ionic-team/ionic/commit/b53ce4b))


### Features

* **config:** strongly typed config ([0169045](https://github.com/ionic-team/ionic/commit/0169045)), closes [#15097](https://github.com/ionic-team/ionic/issues/15097)
* **select:** add open method ([4047812](https://github.com/ionic-team/ionic/commit/4047812)), closes [#14881](https://github.com/ionic-team/ionic/issues/14881)



<a name="4.0.0-beta.2"></a>
# [4.0.0-beta.2](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.1...v4.0.0-beta.2) (2018-08-08)


### Bug Fixes

* **all:** buttons are type="button" ([2b7007f](https://github.com/ionic-team/ionic/commit/2b7007f))
* **app:** fix statusbarPadding ([2c925b7](https://github.com/ionic-team/ionic/commit/2c925b7)), closes [#15073](https://github.com/ionic-team/ionic/issues/15073)
* **chip:** conforms to ion-icon ([f49fa4a](https://github.com/ionic-team/ionic/commit/f49fa4a)), closes [#15053](https://github.com/ionic-team/ionic/issues/15053)
* **content:** remove scroll-inner ([efd77c9](https://github.com/ionic-team/ionic/commit/efd77c9)), closes [#14985](https://github.com/ionic-team/ionic/issues/14985)
* **datetime:** fix gesture ([e9fd184](https://github.com/ionic-team/ionic/commit/e9fd184))
* **datetime:** ionChange event ([8b35e37](https://github.com/ionic-team/ionic/commit/8b35e37))
* **header:** safe margin when statubarPadding=0 ([b69d01d](https://github.com/ionic-team/ionic/commit/b69d01d))
* **input:** hide clear button ([141b86c](https://github.com/ionic-team/ionic/commit/141b86c)), closes [#15002](https://github.com/ionic-team/ionic/issues/15002)
* **menu:** add width and small-width css variables ([#14997](https://github.com/ionic-team/ionic/issues/14997)) ([69f5cc8](https://github.com/ionic-team/ionic/commit/69f5cc8))
* **menu:** content's box-shadow ([48e2a4e](https://github.com/ionic-team/ionic/commit/48e2a4e))
* **nav:** animation backdrop ([948d083](https://github.com/ionic-team/ionic/commit/948d083))
* **popover:** ion-scroll sizing ([b85d4a0](https://github.com/ionic-team/ionic/commit/b85d4a0)), closes [#14911](https://github.com/ionic-team/ionic/issues/14911)
* **range:** value changes when using keyboard ([27fdc9a](https://github.com/ionic-team/ionic/commit/27fdc9a)), closes [#15065](https://github.com/ionic-team/ionic/issues/15065)
* **searchbar:** color ([14d6270](https://github.com/ionic-team/ionic/commit/14d6270)), closes [#14998](https://github.com/ionic-team/ionic/issues/14998)
* **sliding:** fix core gesture logic + priority configuration ([a77ee2a](https://github.com/ionic-team/ionic/commit/a77ee2a)), closes [#14763](https://github.com/ionic-team/ionic/issues/14763)
* **split-pane:** side=end works properly ([dc50003](https://github.com/ionic-team/ionic/commit/dc50003)), closes [#15013](https://github.com/ionic-team/ionic/issues/15013)
* **tab:** edge prop ([2a4327f](https://github.com/ionic-team/ionic/commit/2a4327f)), closes [#15003](https://github.com/ionic-team/ionic/issues/15003)
* **tap-click:** desktop also needs tap-click ([9f4d873](https://github.com/ionic-team/ionic/commit/9f4d873))


### Features

* **core:** add check for standalone mode ([#15001](https://github.com/ionic-team/ionic/issues/15001)) ([0b4b9fe](https://github.com/ionic-team/ionic/commit/0b4b9fe))
* **item-sliding:** adds disabled prop ([9773e2a](https://github.com/ionic-team/ionic/commit/9773e2a)), closes [#14831](https://github.com/ionic-team/ionic/issues/14831)


### Performance Improvements

* **app:** move app css to global css ([a71f382](https://github.com/ionic-team/ionic/commit/a71f382))
* **menu:** flickering ([8253b04](https://github.com/ionic-team/ionic/commit/8253b04))
* **scroll:** filter velocity using exponential moving window ([419ef7b](https://github.com/ionic-team/ionic/commit/419ef7b))



<a name="4.0.0-beta.1"></a>
# [4.0.0-beta.1](https://github.com/ionic-team/ionic/compare/v4.0.0-beta.0...v4.0.0-beta.1) (2018-08-01)


### Bug Fixes

* **accesibility:** boolean aria-* properties ([4f9cbfe](https://github.com/ionic-team/ionic/commit/4f9cbfe))
* **all:** strong type text fields ([1d001a3](https://github.com/ionic-team/ionic/commit/1d001a3))
* **all:** updated tslint rules to latest ([92e21a8](https://github.com/ionic-team/ionic/commit/92e21a8))
* **angular:** events ([7a0545d](https://github.com/ionic-team/ionic/commit/7a0545d)), closes [#14866](https://github.com/ionic-team/ionic/issues/14866)
* **angular:** ion-router-outlet exposes animated ([266336e](https://github.com/ionic-team/ionic/commit/266336e)), closes [#14913](https://github.com/ionic-team/ionic/issues/14913)
* **angular:** pass proper animated value ([7813acc](https://github.com/ionic-team/ionic/commit/7813acc))
* **app:** statusbarPadding ([fd8f875](https://github.com/ionic-team/ionic/commit/fd8f875))
* **app:** user-select on desktop ([8a1ad1d](https://github.com/ionic-team/ionic/commit/8a1ad1d))
* **button:** do not change border radius if round button in toolbar ([#14941](https://github.com/ionic-team/ionic/issues/14941)) ([ad006dd](https://github.com/ionic-team/ionic/commit/ad006dd)), closes [#7661](https://github.com/ionic-team/ionic/issues/7661)
* **button:** improve text style inherency ([25423a0](https://github.com/ionic-team/ionic/commit/25423a0)), closes [#14927](https://github.com/ionic-team/ionic/issues/14927)
* **button:** submit forms using fake button ([c05d672](https://github.com/ionic-team/ionic/commit/c05d672)), closes [#14890](https://github.com/ionic-team/ionic/issues/14890) [#14786](https://github.com/ionic-team/ionic/issues/14786)
* **color:** make desktop selection beautiful ([0cdb500](https://github.com/ionic-team/ionic/commit/0cdb500))
* **config:** avoid using startWith for IE support ([73a9f14](https://github.com/ionic-team/ionic/commit/73a9f14)), closes [#14922](https://github.com/ionic-team/ionic/issues/14922)
* **content:** bottom padding ([be4eda5](https://github.com/ionic-team/ionic/commit/be4eda5))
* **fab:** add styles for disabled ([520da8d](https://github.com/ionic-team/ionic/commit/520da8d)), closes [#14867](https://github.com/ionic-team/ionic/issues/14867)
* **flex-utils:** add missing flex attributes ([7c12e1b](https://github.com/ionic-team/ionic/commit/7c12e1b))
* **input:** add color support for ion-input ([f676f98](https://github.com/ionic-team/ionic/commit/f676f98)), closes [#14864](https://github.com/ionic-team/ionic/issues/14864)
* **inputs:** better customization for placeholder color ([517104f](https://github.com/ionic-team/ionic/commit/517104f))
* **item:** only use pointer cursor for <button> and <a> ([f19553f](https://github.com/ionic-team/ionic/commit/f19553f))
* **pointer-events:** listening to document ([afb0906](https://github.com/ionic-team/ionic/commit/afb0906))
* **refresher:** default to disabled false, add to breaking changes ([f1826a6](https://github.com/ionic-team/ionic/commit/f1826a6)), closes [#14879](https://github.com/ionic-team/ionic/issues/14879)
* **router-outlet:** fix stack attribute detection ([#14921](https://github.com/ionic-team/ionic/issues/14921)) ([16e992a](https://github.com/ionic-team/ionic/commit/16e992a))
* **searchbar:** fix input bluring ([d65174b](https://github.com/ionic-team/ionic/commit/d65174b)), closes [#14916](https://github.com/ionic-team/ionic/issues/14916)
* **slides:** update events to match swipers ([fc0d4c0](https://github.com/ionic-team/ionic/commit/fc0d4c0)), closes [#14865](https://github.com/ionic-team/ionic/issues/14865)
* **title:** can be used nested ([d1969bd](https://github.com/ionic-team/ionic/commit/d1969bd)), closes [#14905](https://github.com/ionic-team/ionic/issues/14905)
* **title:** support color ([7da0ac4](https://github.com/ionic-team/ionic/commit/7da0ac4))


### Features

* **menu:** configurable using menuType ([a62759c](https://github.com/ionic-team/ionic/commit/a62759c)), closes [#14901](https://github.com/ionic-team/ionic/issues/14901)


### Performance Improvements

* **app:** tap-click is a ES ([b0ac5ba](https://github.com/ionic-team/ionic/commit/b0ac5ba))
* **css:** always emit compressed css ([143f0f0](https://github.com/ionic-team/ionic/commit/143f0f0))
* **gesture:** lazy loaded dynamic ES module ([49cac8b](https://github.com/ionic-team/ionic/commit/49cac8b))
* **icon:** disable icon lazy loading when it's not needed ([7292fc7](https://github.com/ionic-team/ionic/commit/7292fc7))



<a name="4.0.0-beta.0"></a>
# [4.0.0-beta.0](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.14...v4.0.0-beta.0) (2018-07-25)

## Enjoy! :tada:


### Bug Fixes

* **angular:** always dispatch lifecycle events ([5677daa](https://github.com/ionic-team/ionic/commit/5677daa))



<a name="4.0.0-alpha.14"></a>
# [4.0.0-alpha.14](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.13...v4.0.0-alpha.14) (2018-07-25)


### Bug Fixes

* **angular:** hide pages properly ([a44b844](https://github.com/ionic-team/ionic/commit/a44b844))
* **angular:** make pages invisible before they are rendered ([a589816](https://github.com/ionic-team/ionic/commit/a589816))
* **transition:** make sure hidden is removed ([f52dece](https://github.com/ionic-team/ionic/commit/f52dece))



<a name="4.0.0-alpha.13"></a>
# [4.0.0-alpha.13](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.12...v4.0.0-alpha.13) (2018-07-24)


### Bug Fixes

* **css:** revert hidden css ([7d3d98d](https://github.com/ionic-team/ionic/commit/7d3d98d))
* **tab:** prevent infinite loop ([05b258c](https://github.com/ionic-team/ionic/commit/05b258c))
* **toolbar:** remove transparent border on translucent toolbar ([55cb354](https://github.com/ionic-team/ionic/commit/55cb354))



<a name="4.0.0-alpha.12"></a>
# [4.0.0-alpha.12](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.11...v4.0.0-alpha.12) (2018-07-24)


### Bug Fixes

* **all:** accesibility and global styles for hidden nodes ([4b844ef](https://github.com/ionic-team/ionic/commit/4b844ef))
* **checkbox:** get css variable customization working better ([3e7aa4b](https://github.com/ionic-team/ionic/commit/3e7aa4b))
* **content:** set height to make it accessible for children elements ([#14772](https://github.com/ionic-team/ionic/issues/14772)) ([857b42d](https://github.com/ionic-team/ionic/commit/857b42d))
* **grid:** set the flex and width to auto when size is auto ([ba30671](https://github.com/ionic-team/ionic/commit/ba30671)), closes [#14807](https://github.com/ionic-team/ionic/issues/14807)
* **inputs:** inputs work inside <form> ([8324bd1](https://github.com/ionic-team/ionic/commit/8324bd1))
* **label:** style color ([5c0e9e6](https://github.com/ionic-team/ionic/commit/5c0e9e6))
* **list:** hide the last item border when there are no lines ([#14770](https://github.com/ionic-team/ionic/issues/14770)) ([26f7379](https://github.com/ionic-team/ionic/commit/26f7379)), closes [#14769](https://github.com/ionic-team/ionic/issues/14769)
* **margin:** adds css variables ([f6c8f3f](https://github.com/ionic-team/ionic/commit/f6c8f3f)), closes [#14798](https://github.com/ionic-team/ionic/issues/14798) [#14826](https://github.com/ionic-team/ionic/issues/14826)
* **menu-button:** fix sass linting ([d22f04b](https://github.com/ionic-team/ionic/commit/d22f04b))
* **menu-button:** get proper styles when used inside ion-buttons ([811eee7](https://github.com/ionic-team/ionic/commit/811eee7))
* **modal:** use flex to position modal to make it easier to size ([9488a98](https://github.com/ionic-team/ionic/commit/9488a98)), closes [#14392](https://github.com/ionic-team/ionic/issues/14392)
* **overlay:** remove global css vars in overlays for local ones ([38b1e47](https://github.com/ionic-team/ionic/commit/38b1e47))
* **refresher:** find parent ion-content properly ([4eab209](https://github.com/ionic-team/ionic/commit/4eab209)), closes [#14833](https://github.com/ionic-team/ionic/issues/14833)
* **slides:** swiper container should take up 100% height ([1d201ec](https://github.com/ionic-team/ionic/commit/1d201ec)), closes [#14771](https://github.com/ionic-team/ionic/issues/14771)
* **spinner:** color can be customized in non-shadow-dom ([65008e7](https://github.com/ionic-team/ionic/commit/65008e7))
* **spinner:** get paused attribute working and update tests ([3ab1e2d](https://github.com/ionic-team/ionic/commit/3ab1e2d)), closes [#14811](https://github.com/ionic-team/ionic/issues/14811)


### Features

* **button:** overflow is configurable ([ddb1e49](https://github.com/ionic-team/ionic/commit/ddb1e49)), closes [#14839](https://github.com/ionic-team/ionic/issues/14839)
* **menu:** add getWidth() ([cb4acab](https://github.com/ionic-team/ionic/commit/cb4acab)), closes [#14794](https://github.com/ionic-team/ionic/issues/14794)



<a name="4.0.0-alpha.11"></a>
# [4.0.0-alpha.11](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.10...v4.0.0-alpha.11) (2018-07-16)


### Bug Fixes

* **anchor:** add proper styling, support for colors, and basic test ([1dbf5bb](https://github.com/ionic-team/ionic/commit/1dbf5bb)), closes [#14777](https://github.com/ionic-team/ionic/issues/14777)
* **anchor:** inner <a> inherits text styles ([9aedfc6](https://github.com/ionic-team/ionic/commit/9aedfc6))
* **button:** add box-sizing so anchor buttons won't exceed max-width ([9c9f081](https://github.com/ionic-team/ionic/commit/9c9f081)), closes [#14760](https://github.com/ionic-team/ionic/issues/14760)
* **button:** set display type on host ([89d1526](https://github.com/ionic-team/ionic/commit/89d1526))
* **button:** submit form w/ ion-button within shadow dom ([4ed8541](https://github.com/ionic-team/ionic/commit/4ed8541)), closes [#14776](https://github.com/ionic-team/ionic/issues/14776)
* **item:** add cursor pointer back to native item ([43f1fec](https://github.com/ionic-team/ionic/commit/43f1fec)), closes [#14743](https://github.com/ionic-team/ionic/issues/14743)
* **searchbar:** use tag in toolbar context selector ([124b87c](https://github.com/ionic-team/ionic/commit/124b87c))
* **segment:** add styles for in a color toolbar ([d9e4ca7](https://github.com/ionic-team/ionic/commit/d9e4ca7))
* **spinner:** style CSS props ([2798bb0](https://github.com/ionic-team/ionic/commit/2798bb0))
* **tab:** props are reactive ([00c4c77](https://github.com/ionic-team/ionic/commit/00c4c77))
* **tab-button:** add a class to hide the tab when show is false ([eb9ed17](https://github.com/ionic-team/ionic/commit/eb9ed17))
* **tabs:** add the colors to the tabbar as well ([5348e7c](https://github.com/ionic-team/ionic/commit/5348e7c)), closes [#14758](https://github.com/ionic-team/ionic/issues/14758)
* **tabs:** fix the tabs so the color property works on tab button ([8aed3bf](https://github.com/ionic-team/ionic/commit/8aed3bf)), closes [#14758](https://github.com/ionic-team/ionic/issues/14758)
* **virtual-scroll:** read viewport size for every scroll event ([1d3eb3f](https://github.com/ionic-team/ionic/commit/1d3eb3f))



<a name="4.0.0-alpha.10"></a>
# [4.0.0-alpha.10](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.9...v4.0.0-alpha.10) (2018-07-11)


### Bug Fixes

* **angular:** publish css to npm ([748c209](https://github.com/ionic-team/ionic/commit/748c209))
* **item:** pass the correct type property to the button tag ([5f8b02e](https://github.com/ionic-team/ionic/commit/5f8b02e)), closes [#14740](https://github.com/ionic-team/ionic/issues/14740)
* **tabs:** correct alignment for label/icon only tabs ([b46c3e2](https://github.com/ionic-team/ionic/commit/b46c3e2))
* **tabs:** update the tabbar placement value to match the property it applies to ([45583bc](https://github.com/ionic-team/ionic/commit/45583bc))
* **toolbar:** get translucency working with header, footer and toolbar ([f6ab5b6](https://github.com/ionic-team/ionic/commit/f6ab5b6))



<a name="4.0.0-alpha.9"></a>
# [4.0.0-alpha.9](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.8...v4.0.0-alpha.9) (2018-07-10)


### Bug Fixes

* **angular:** esm ([0e68f17](https://github.com/ionic-team/ionic/commit/0e68f17))


<a name="4.0.0-alpha.8"></a>
# [4.0.0-alpha.8](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.7...v4.0.0-alpha.8) (2018-07-09)


### Bug Fixes

* **angular:** avoid TS 2.8 features ([c736bac](https://github.com/ionic-team/ionic/commit/c736bac))
* **angular:** correct subscription to cordova ready event ([#14577](https://github.com/ionic-team/ionic/issues/14577)) ([5967352](https://github.com/ionic-team/ionic/commit/5967352))
* **bundling:** fix EventEmitter import ([8e47101](https://github.com/ionic-team/ionic/commit/8e47101))
* linting ([e629e29](https://github.com/ionic-team/ionic/commit/e629e29))
* **icon:** target element for style and add to breaking ([949d93e](https://github.com/ionic-team/ionic/commit/949d93e))
* **overlay:** make type an any ([15dc651](https://github.com/ionic-team/ionic/commit/15dc651))
* **router:** fix reuse strategy ([bd53bba](https://github.com/ionic-team/ionic/commit/bd53bba))
* **scripts:** update github release notes ([fc078af](https://github.com/ionic-team/ionic/commit/fc078af))
* **tabs:** align tab title and icons to flex-start ([c11d74b](https://github.com/ionic-team/ionic/commit/c11d74b)), closes [#14606](https://github.com/ionic-team/ionic/issues/14606)


### Features

* **all:** custom icons ([e6638e7](https://github.com/ionic-team/ionic/commit/e6638e7))
* **dir:** default to ltr css, rtl overrides w/ [dir=rtl] selectors ([fb4353c](https://github.com/ionic-team/ionic/commit/fb4353c))
* **slides:** update swiper to latest ([8e164d6](https://github.com/ionic-team/ionic/commit/8e164d6))



<a name="4.0.0-alpha.7"></a>
# [4.0.0-alpha.7](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.6...v4.0.0-alpha.7) (2018-05-17)


### Bug Fixes

* **all:** strong typing for color ([618f708](https://github.com/ionic-team/ionic/commit/618f708))
* **angular:** platform logic belongs to core ([af5db2f](https://github.com/ionic-team/ionic/commit/af5db2f))
* **angular:** build script ([a88e1e8](https://github.com/ionic-team/ionic/commit/a88e1e8))
* **angular:** params are assigned to props ([7fa6e43](https://github.com/ionic-team/ionic/commit/7fa6e43))
* **angular:** populated the platforms array ([#14466](https://github.com/ionic-team/ionic/issues/14466)) ([d177087](https://github.com/ionic-team/ionic/commit/d177087))
* **angular:** Required<> is not available ([8aa6965](https://github.com/ionic-team/ionic/commit/8aa6965))
* **angular:** routerLink integration ([ed8ff4f](https://github.com/ionic-team/ionic/commit/ed8ff4f))
* **content:** scrol-inner takes all height ([3da0c98](https://github.com/ionic-team/ionic/commit/3da0c98))
* **nav:** Remove console.log ([#14467](https://github.com/ionic-team/ionic/issues/14467)) ([d93b1d5](https://github.com/ionic-team/ionic/commit/d93b1d5))
* **refresher:** adds threshold ([34ae904](https://github.com/ionic-team/ionic/commit/34ae904))
* **router:** accepts root direction ([ae9d0c7](https://github.com/ionic-team/ionic/commit/ae9d0c7))
* **router:** fix push() public interface ([875b9d0](https://github.com/ionic-team/ionic/commit/875b9d0))


### Features

* **img:** adds lazy load image ([b06c65f](https://github.com/ionic-team/ionic/commit/b06c65f))



<a name="4.0.0-alpha.6"></a>
# [4.0.0-alpha.6](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.5...v4.0.0-alpha.6) (2018-05-10)


### Bug Fixes

* **angular:** aot ([714f4a6](https://github.com/ionic-team/ionic/commit/714f4a6))



<a name="4.0.0-alpha.5"></a>
# [4.0.0-alpha.5](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.4...v4.0.0-alpha.5) (2018-05-10)


### Bug Fixes

* **alert:** onDidDismiss() is called ([7b33039](https://github.com/ionic-team/ionic/commit/7b33039))
* **all:** snapshot tests ([cc7ab4e](https://github.com/ionic-team/ionic/commit/cc7ab4e))
* **angular:** exports ([50021cd](https://github.com/ionic-team/ionic/commit/50021cd))
* **angular:** routerLink uses <a> ([526c9a8](https://github.com/ionic-team/ionic/commit/526c9a8))
* **angular:** setup config provider correctly ([82fbe31](https://github.com/ionic-team/ionic/commit/82fbe31))
* **angular:** unexport some es2017 js ([f7bcb68](https://github.com/ionic-team/ionic/commit/f7bcb68))
* **app:** fix the statusbar-padding to match new structure ([6c2d539](https://github.com/ionic-team/ionic/commit/6c2d539))
* **back-button:** fix position ([e00da6d](https://github.com/ionic-team/ionic/commit/e00da6d))
* **capacitor:** detect capacitor native ([23d86eb](https://github.com/ionic-team/ionic/commit/23d86eb))
* **hover:** remove ion-app .enable-hover css ([a939fa2](https://github.com/ionic-team/ionic/commit/a939fa2))
* **inputs:** interactive css to rule all them ([1bd5467](https://github.com/ionic-team/ionic/commit/1bd5467))
* **refresher:** move gesture target to content ([df2faa4](https://github.com/ionic-team/ionic/commit/df2faa4))
* **router:** change events when URL changes ([ece86ee](https://github.com/ionic-team/ionic/commit/ece86ee))
* **router:** dynamic redirects ([ba551fd](https://github.com/ionic-team/ionic/commit/ba551fd))
* **router:** route information is stateless ([0f8477d](https://github.com/ionic-team/ionic/commit/0f8477d))
* **snapshot:** using md mode ([e352d1b](https://github.com/ionic-team/ionic/commit/e352d1b))
* **theming:** update contrast colors ([ae1028d](https://github.com/ionic-team/ionic/commit/ae1028d))
* **virtual-scroll:** JSX can render headers and footers ([012127d](https://github.com/ionic-team/ionic/commit/012127d))
* **virtual-scroll:** linting ([df8a4f7](https://github.com/ionic-team/ionic/commit/df8a4f7))


### Performance Improvements

* **all:** dynamic import ([bb809b6](https://github.com/ionic-team/ionic/commit/bb809b6))



<a name="4.0.0-alpha.4"></a>
# [4.0.0-alpha.4](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.3...v4.0.0-alpha.4) (2018-04-30)


### Bug Fixes

* **angular:** compare router params length ([b3a9c7f](https://github.com/ionic-team/ionic/commit/b3a9c7f))
* **angular:** Config provider ([329a348](https://github.com/ionic-team/ionic/commit/329a348))
* **angular:** platform.ready() returns type ([c0ec02e](https://github.com/ionic-team/ionic/commit/c0ec02e))
* **angular:** update proxies ([da0bfc7](https://github.com/ionic-team/ionic/commit/da0bfc7))
* **config:** add object.entries polyfil ([c917a3c](https://github.com/ionic-team/ionic/commit/c917a3c))
* **config:** add setupConfig util ([0c1476e](https://github.com/ionic-team/ionic/commit/0c1476e))
* **lint:** import order ([8b1452c](https://github.com/ionic-team/ionic/commit/8b1452c))
* **nav:** rename animate to animated ([98a3519](https://github.com/ionic-team/ionic/commit/98a3519))
* **prerender:** router compatible with prerender ([9c7b0ca](https://github.com/ionic-team/ionic/commit/9c7b0ca))
* **router:** error when it can't initialize property ([e56b2ee](https://github.com/ionic-team/ionic/commit/e56b2ee))
* **router:** initial load waits until outlet attaches ([c905ba4](https://github.com/ionic-team/ionic/commit/c905ba4))
* **router:** root prop ([89d5a35](https://github.com/ionic-team/ionic/commit/89d5a35))
* **router:** writeURL() for non root base ([af4bcb8](https://github.com/ionic-team/ionic/commit/af4bcb8))
* **scripts:** github release ([545d3c2](https://github.com/ionic-team/ionic/commit/545d3c2))
* **segment:** checked can be changed dynamically ([78454b4](https://github.com/ionic-team/ionic/commit/78454b4))
* **select:** cssClass + strong typed ([826e02b](https://github.com/ionic-team/ionic/commit/826e02b))
* **toast:** only use constant and env if supported ([#14399](https://github.com/ionic-team/ionic/issues/14399)) ([9bee0f0](https://github.com/ionic-team/ionic/commit/9bee0f0))
* **validate:** fix type errors ([3328314](https://github.com/ionic-team/ionic/commit/3328314))


### Features

* **router:** add willChange event ([d613411](https://github.com/ionic-team/ionic/commit/d613411))



<a name="4.0.0-alpha.3"></a>
# [4.0.0-alpha.3](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.2...v4.0.0-alpha.3) (2018-04-23)


### Bug Fixes

* **all:** strong typed events ([d5129df](https://github.com/ionic-team/ionic/commit/d5129df))
* **angular:** adds missing events ([c929dad](https://github.com/ionic-team/ionic/commit/c929dad))
* **angular:** Config provider ([c87f0c5](https://github.com/ionic-team/ionic/commit/c87f0c5))
* **angular:** platform ready() ([2b3c14b](https://github.com/ionic-team/ionic/commit/2b3c14b))
* **overlay:** cssClasses applied to overlay ([43d7538](https://github.com/ionic-team/ionic/commit/43d7538))
* **prerender:** local references to window/document ([78bd146](https://github.com/ionic-team/ionic/commit/78bd146))
* **virtual-scroll:** queue.write ([c1cbbc5](https://github.com/ionic-team/ionic/commit/c1cbbc5))


### Features

* **angular:** animation is explicit ([099b3ed](https://github.com/ionic-team/ionic/commit/099b3ed))


### Performance Improvements

* **platform:** remove from critical path ([86a6cde](https://github.com/ionic-team/ionic/commit/86a6cde))



<a name="4.0.0-alpha.2"></a>
# [4.0.0-alpha.2](https://github.com/ionic-team/ionic/compare/v4.0.0-alpha.1...v4.0.0-alpha.2) (2018-04-13)


### Bug Fixes

* **angular:** add NavParams ([22ebbce](https://github.com/ionic-team/ionic/commit/22ebbce))
* **angular:** change detection in deep ViewContainers ([850d7fc](https://github.com/ionic-team/ionic/commit/850d7fc))
* **angular:** emit es5 code ([02c1e83](https://github.com/ionic-team/ionic/commit/02c1e83))
* **angular:** icon proxy ([db5313e](https://github.com/ionic-team/ionic/commit/db5313e))
* **angular:** router-outlet uses stack by default ([5c91101](https://github.com/ionic-team/ionic/commit/5c91101))
* **angular:** using es2017 types ([12a27bc](https://github.com/ionic-team/ionic/commit/12a27bc))
* **angular:** viewContainer in overlays ([8ad3df9](https://github.com/ionic-team/ionic/commit/8ad3df9))
* **back-button:** get the back button color working ([5f4250b](https://github.com/ionic-team/ionic/commit/5f4250b))
* **fab:** fix fab activation ([a203534](https://github.com/ionic-team/ionic/commit/a203534))
* **label:** inline position by default ([fde878b](https://github.com/ionic-team/ionic/commit/fde878b))
* **label:** using prop for position ([b1ee4b8](https://github.com/ionic-team/ionic/commit/b1ee4b8)), closes [#14288](https://github.com/ionic-team/ionic/issues/14288)
* **mode:** set mode css class on ion-app ([fcb08e1](https://github.com/ionic-team/ionic/commit/fcb08e1))
* **props:** update stencil ([ea24ad6](https://github.com/ionic-team/ionic/commit/ea24ad6))
* **react:** FrameworkDelegate matches API ([e40a6b0](https://github.com/ionic-team/ionic/commit/e40a6b0))
* **toast:** account for safe-area on ios ([d984214](https://github.com/ionic-team/ionic/commit/d984214))


### Features

* **angular:** adds DomController ([6a31f39](https://github.com/ionic-team/ionic/commit/6a31f39)), closes [#14286](https://github.com/ionic-team/ionic/issues/14286)
* **angular:** push/setRoot/pop ([4d23cba](https://github.com/ionic-team/ionic/commit/4d23cba))
* **DomController:** add DomController provider using stencil queue ([bceece7](https://github.com/ionic-team/ionic/commit/bceece7))
* **queue:** use stencil's queue controller for dom read/writes ([d623b3b](https://github.com/ionic-team/ionic/commit/d623b3b))
* **router:** dont reuse the component if the params are different ([5899b03](https://github.com/ionic-team/ionic/commit/5899b03))
* **routerDirection:** refactors goBack ([54d7a12](https://github.com/ionic-team/ionic/commit/54d7a12))



<a name="4.0.0-alpha.1"></a>
# [4.0.0-alpha.1](https://github.com/ionic-team/ionic/compare/v0.2.2...v4.0.0-alpha.1) (2018-04-06)


### Bug Fixes

* **angular:** change detection ([79ba639](https://github.com/ionic-team/ionic/commit/79ba639))
* **angular:** proxy methods ([5153da4](https://github.com/ionic-team/ionic/commit/5153da4))
* **angular:** proxy outputs ([64a9497](https://github.com/ionic-team/ionic/commit/64a9497))
* **menu:** prerender ([a3cd5db](https://github.com/ionic-team/ionic/commit/a3cd5db))
* **split-pane:** prerender ([c6e962c](https://github.com/ionic-team/ionic/commit/c6e962c))



<a name="0.2.2"></a>
## [0.2.2](https://github.com/ionic-team/ionic/compare/v0.2.1...v0.2.2) (2018-04-05)


### Bug Fixes

* **back-button:** fix menu and back button alignment ([#14268](https://github.com/ionic-team/ionic/issues/14268)) ([57fbf6c](https://github.com/ionic-team/ionic/commit/57fbf6c))
* **ripple-effect:** animation ([25c852c](https://github.com/ionic-team/ionic/commit/25c852c))
* **sass:** add missing alert css properties ([#14269](https://github.com/ionic-team/ionic/issues/14269)) ([3471dd6](https://github.com/ionic-team/ionic/commit/3471dd6)), closes [#14258](https://github.com/ionic-team/ionic/issues/14258)
* **script:** release script pushes tags ([d23108a](https://github.com/ionic-team/ionic/commit/d23108a))
* **scripts:** improve script ([2215c6a](https://github.com/ionic-team/ionic/commit/2215c6a))
* **select:** pass header and subHeader to interfaces ([2195895](https://github.com/ionic-team/ionic/commit/2195895))
* **select:** wrap the text for the message in a popover ([0a0959b](https://github.com/ionic-team/ionic/commit/0a0959b))



<a name="0.2.1"></a>
## [0.2.1](https://github.com/ionic-team/ionic/compare/v0.2.0...v0.2.1) (2018-04-04)


### Bug Fixes

* **angular:** back button prevents default ([4db687e](https://github.com/ionic-team/ionic/commit/4db687e))
* **angular:** back-button ([1f78390](https://github.com/ionic-team/ionic/commit/1f78390))
* **angular:** back-button does not push view ([bb46b5f](https://github.com/ionic-team/ionic/commit/bb46b5f))
* **angular:** tabs flickering ([7e97006](https://github.com/ionic-team/ionic/commit/7e97006))
* **app:** hide elements ([11cb42f](https://github.com/ionic-team/ionic/commit/11cb42f))
* **scripts:** update dep version ([974b949](https://github.com/ionic-team/ionic/commit/974b949))


### Features

* **angular:** href integration ([09e6b7e](https://github.com/ionic-team/ionic/commit/09e6b7e))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/ionic-team/ionic/compare/v0.1.6...v0.2.0) (2018-04-02)


### Bug Fixes

* **angular:** URL based tabs ([14fedb9](https://github.com/ionic-team/ionic/commit/14fedb9))



<a name="0.1.6"></a>
## [0.1.6](https://github.com/ionic-team/ionic/compare/v0.1.5...v0.1.6) (2018-04-02)


### Bug Fixes

* **angular:** lifecycles ([062641d](https://github.com/ionic-team/ionic/commit/062641d))
* **angular:** modal and popover ([acd411d](https://github.com/ionic-team/ionic/commit/acd411d))
* **angular:** module exports ([cece447](https://github.com/ionic-team/ionic/commit/cece447))
* **angular:** proxies ([2308239](https://github.com/ionic-team/ionic/commit/2308239))
* **angular:** tabs angular tests ([ff1ed88](https://github.com/ionic-team/ionic/commit/ff1ed88))
* **router-outlet:** enteringEl !== leavingEl ([0d44253](https://github.com/ionic-team/ionic/commit/0d44253))
* **router-outlet:** mutable prop ([ff06dab](https://github.com/ionic-team/ionic/commit/ff06dab))



<a name="0.1.5"></a>
## [0.1.5](https://github.com/ionic-team/ionic/compare/v0.1.4...v0.1.5) (2018-03-29)


### Bug Fixes

* **all:** absolute positioning ([4fcddad](https://github.com/ionic-team/ionic/commit/4fcddad))
* **angular:** goback navigation ([7b9a00e](https://github.com/ionic-team/ionic/commit/7b9a00e))
* **angular:** ion-back-button ([9c789ce](https://github.com/ionic-team/ionic/commit/9c789ce))
* **angular:** stack based navigation ([726938f](https://github.com/ionic-team/ionic/commit/726938f))
* **avatar:** adjust wide images to fill instead of squish ([b0f8ca5](https://github.com/ionic-team/ionic/commit/b0f8ca5))
* **back-button:** empty text is a valid value ([eb0ff2f](https://github.com/ionic-team/ionic/commit/eb0ff2f))
* **back-button:** ios style ([2b8e489](https://github.com/ionic-team/ionic/commit/2b8e489))
* **button:** dynamic bar-button ([d0c5f53](https://github.com/ionic-team/ionic/commit/d0c5f53))
* **checkbox:** update ios checkbox to be closer to native ([b29fce1](https://github.com/ionic-team/ionic/commit/b29fce1))
* **components:** add font-smoothing to mixing components ([9caeec7](https://github.com/ionic-team/ionic/commit/9caeec7))
* **covers:** absolute positioning ([ce09978](https://github.com/ionic-team/ionic/commit/ce09978))
* **item-option:** remove outline on active/focus ([eae6869](https://github.com/ionic-team/ionic/commit/eae6869)), closes [#14191](https://github.com/ionic-team/ionic/issues/14191)
* **label:** add missing text-wrap styles for ios ([a9bd76a](https://github.com/ionic-team/ionic/commit/a9bd76a)), closes [#13157](https://github.com/ionic-team/ionic/issues/13157)
* **menu:** default menu mode ([c31bcde](https://github.com/ionic-team/ionic/commit/c31bcde))
* **nav:** animated opts ([57a5d49](https://github.com/ionic-team/ionic/commit/57a5d49))
* **nav:** no animation ([4fdfddb](https://github.com/ionic-team/ionic/commit/4fdfddb))
* **nav:** transition name ([011a374](https://github.com/ionic-team/ionic/commit/011a374))
* **picker:** do not scroll ([1c06bfe](https://github.com/ionic-team/ionic/commit/1c06bfe))
* **ripple-effect:** tapclick is required in ionic ([d57122c](https://github.com/ionic-team/ionic/commit/d57122c))
* **router:** change detection for componentProps ([a718f7e](https://github.com/ionic-team/ionic/commit/a718f7e))
* **router:** explicit goback should not push ([7a26162](https://github.com/ionic-team/ionic/commit/7a26162))
* **router:** fixes navChanged() ([dddaee1](https://github.com/ionic-team/ionic/commit/dddaee1))
* **router:** ion-nav ([113af9e](https://github.com/ionic-team/ionic/commit/113af9e))
* **router:** loging ([ffaec16](https://github.com/ionic-team/ionic/commit/ffaec16))
* **router:** route change detection ([9e9f2a2](https://github.com/ionic-team/ionic/commit/9e9f2a2))
* **router:** wait RAF ([b26a563](https://github.com/ionic-team/ionic/commit/b26a563))
* **slides:** unload slides correctly ([59c6891](https://github.com/ionic-team/ionic/commit/59c6891))
* **thumbnail:** adjust wide images to fill instead of squish ([54558c9](https://github.com/ionic-team/ionic/commit/54558c9))
* **toast:** dismiss timeout ([44f343d](https://github.com/ionic-team/ionic/commit/44f343d))
* **toolbar:** unused private ([c9d2a0d](https://github.com/ionic-team/ionic/commit/c9d2a0d))
* **transition:** nav ios transition ([095f9c8](https://github.com/ionic-team/ionic/commit/095f9c8))


### Features

* **button:** goback attribute ([00fc460](https://github.com/ionic-team/ionic/commit/00fc460))
* **config:** add set to config ([69a6f8d](https://github.com/ionic-team/ionic/commit/69a6f8d))
* **content:** scrollEnabled ([5c2678f](https://github.com/ionic-team/ionic/commit/5c2678f))
* **menu-controller:** expose registerAnimation ([153f8ca](https://github.com/ionic-team/ionic/commit/153f8ca))
* **nav:** goBack directive ([862e571](https://github.com/ionic-team/ionic/commit/862e571))
* **nav-controller:** goback best guess ([46bbd0f](https://github.com/ionic-team/ionic/commit/46bbd0f))
* **ripple:** css variable color ([77fc792](https://github.com/ionic-team/ionic/commit/77fc792))
* **tab:** framework support ([48d1bd4](https://github.com/ionic-team/ionic/commit/48d1bd4))


### Performance Improvements

* **app:** platform is not needed ([e681836](https://github.com/ionic-team/ionic/commit/e681836))


### Reverts

* **toolbar:** revert to use old button attributes ([574c346](https://github.com/ionic-team/ionic/commit/574c346)), closes [#14172](https://github.com/ionic-team/ionic/issues/14172)



<a name="0.1.4"></a>
## [0.1.4](https://github.com/ionic-team/ionic/compare/v0.1.4-9...v0.1.4) (2018-03-21)


### Bug Fixes

* **action-sheet:** update padding on title to match native ([f0a40fa](https://github.com/ionic-team/ionic/commit/f0a40fa))
* **alert:** update colors for alert text and input borders ([605ec93](https://github.com/ionic-team/ionic/commit/605ec93)), closes [#14196](https://github.com/ionic-team/ionic/issues/14196)
* **alert:** update md alert to closer match spec ([7d53e49](https://github.com/ionic-team/ionic/commit/7d53e49))
* **all:** ts strict (part 4) ([4693229](https://github.com/ionic-team/ionic/commit/4693229))
* **angular:** router-outlet animation ([943e2f7](https://github.com/ionic-team/ionic/commit/943e2f7))
* **chip:** use lighter background color ([08553f1](https://github.com/ionic-team/ionic/commit/08553f1)), closes [#14196](https://github.com/ionic-team/ionic/issues/14196)
* **picker:** does not scroll ([b49a45d](https://github.com/ionic-team/ionic/commit/b49a45d))
* **router:** reusing checks params ([371fc19](https://github.com/ionic-team/ionic/commit/371fc19))
* **router-outlet:** css and change logic ([6e683c5](https://github.com/ionic-team/ionic/commit/6e683c5))


### Features

* **fab:** add box shadow and transition for ios ([d26074a](https://github.com/ionic-team/ionic/commit/d26074a))
* **ion-router-outlet:** adds router-outlet ([c03afab](https://github.com/ionic-team/ionic/commit/c03afab))



<a name="0.1.4-9"></a>
## [0.1.4-9](https://github.com/ionic-team/ionic/compare/v0.1.4-8...v0.1.4-9) (2018-03-20)


### Bug Fixes

* **all:** ts strict (part 3) ([06ad60e](https://github.com/ionic-team/ionic/commit/06ad60e))
* **angular:** ion-nav no routing ([9094c66](https://github.com/ionic-team/ionic/commit/9094c66))
* **angular:** removeViewFromDom ([41f54f8](https://github.com/ionic-team/ionic/commit/41f54f8))
* **back-button:** use correct color for ios back button ([b82c382](https://github.com/ionic-team/ionic/commit/b82c382)), closes [#14177](https://github.com/ionic-team/ionic/issues/14177)
* **overlays:** page is removed properly ([9988c75](https://github.com/ionic-team/ionic/commit/9988c75))
* **theming:** update spinner classes to new names ([f578122](https://github.com/ionic-team/ionic/commit/f578122))


### Features

* **angular:** ion-nav ([f39d3ad](https://github.com/ionic-team/ionic/commit/f39d3ad))



<a name="0.1.4-8"></a>
## [0.1.4-8](https://github.com/ionic-team/ionic/compare/v0.1.4-7...v0.1.4-8) (2018-03-19)


### Bug Fixes

* **back-button:** apply the proper color to the back button ([7d2de18](https://github.com/ionic-team/ionic/commit/7d2de18)), closes [#14177](https://github.com/ionic-team/ionic/issues/14177)


### Features

* **nav:** support for rootParams ([50abcf5](https://github.com/ionic-team/ionic/commit/50abcf5))



<a name="0.1.4-7"></a>
## [0.1.4-7](https://github.com/ionic-team/ionic/compare/v0.1.4-6...v0.1.4-7) (2018-03-16)


### Features

* **router:** wildcard redirects ([2bdf4ad](https://github.com/ionic-team/ionic/commit/2bdf4ad))



<a name="0.1.4-6"></a>
## [0.1.4-6](https://github.com/ionic-team/ionic/compare/v0.1.4-5...v0.1.4-6) (2018-03-15)


### Bug Fixes

* **alert:** backdrop calls cancel handler ([de22eca](https://github.com/ionic-team/ionic/commit/de22eca))
* **alert:** set input value ([6e2a9c9](https://github.com/ionic-team/ionic/commit/6e2a9c9))
* **angular:** create angular delegate ([3b5f758](https://github.com/ionic-team/ionic/commit/3b5f758))
* **angular:** fix overlays ([cc4fecc](https://github.com/ionic-team/ionic/commit/cc4fecc))
* **angular:** modal and popover support ([9a0755a](https://github.com/ionic-team/ionic/commit/9a0755a))
* **demos:** fixes angular ([f398b3a](https://github.com/ionic-team/ionic/commit/f398b3a))
* **overlay:** using hostData for zIndex ([64f0866](https://github.com/ionic-team/ionic/commit/64f0866))
* **overlay:** wrong stencil import ([22f6a34](https://github.com/ionic-team/ionic/commit/22f6a34))
* **overlays:** OverlayController interface ([6e2ca85](https://github.com/ionic-team/ionic/commit/6e2ca85))
* **popover:** lifecycles ([b56c2a8](https://github.com/ionic-team/ionic/commit/b56c2a8))
* **router:** ambiguous routes ([b4f46ee](https://github.com/ionic-team/ionic/commit/b4f46ee))
* **router:** fix selection ([207f416](https://github.com/ionic-team/ionic/commit/207f416))
* **router:** rename API to match stencil-router ([e729610](https://github.com/ionic-team/ionic/commit/e729610))
* **router:** retuning string path ([f48d817](https://github.com/ionic-team/ionic/commit/f48d817))
* **toggle:** ios shadow ([7df023a](https://github.com/ionic-team/ionic/commit/7df023a))


### Features

* **ion-router:** dynamic routes ([7c3cba0](https://github.com/ionic-team/ionic/commit/7c3cba0))
* **overlay:** adds lifecycle events ([0b099ce](https://github.com/ionic-team/ionic/commit/0b099ce))
* **overlays:** adds onDidDismiss and onWillDismiss ([7dcf8a5](https://github.com/ionic-team/ionic/commit/7dcf8a5))


### Performance Improvements

* **scss:** optimize multi dir ([#14156](https://github.com/ionic-team/ionic/issues/14156)) ([ba63d01](https://github.com/ionic-team/ionic/commit/ba63d01))



<a name="0.1.4-5"></a>
## [0.1.4-5](https://github.com/ionic-team/ionic/compare/v0.1.4-4...v0.1.4-5) (2018-03-09)


### Bug Fixes

* **item:** button outline ([f671008](https://github.com/ionic-team/ionic/commit/f671008))
* **router:** fix flickering ([f2ac6e3](https://github.com/ionic-team/ionic/commit/f2ac6e3))
* **router:** flickering 2 ([88f2981](https://github.com/ionic-team/ionic/commit/88f2981))
* **router:** tslint ([1ace045](https://github.com/ionic-team/ionic/commit/1ace045))


### Features

* **router:** adds redirectTo ([f5c6333](https://github.com/ionic-team/ionic/commit/f5c6333))



<a name="0.1.4-4"></a>
## [0.1.4-4](https://github.com/ionic-team/ionic/compare/v0.1.4-3...v0.1.4-4) (2018-03-08)


### Bug Fixes

* **back-button:** implements back animation ([64a787a](https://github.com/ionic-team/ionic/commit/64a787a))
* **route:** params is not undefined ([8b6df5a](https://github.com/ionic-team/ionic/commit/8b6df5a))



<a name="0.1.4-3"></a>
## [0.1.4-3](https://github.com/ionic-team/ionic/compare/v0.1.4-2...v0.1.4-3) (2018-03-08)


### Bug Fixes

* **router:** passing params to ion-nav ([d1263a8](https://github.com/ionic-team/ionic/commit/d1263a8))


### Features

* **back-button:** adds defaultHref ([5271f68](https://github.com/ionic-team/ionic/commit/5271f68))
* **nav:** params ([878d7e6](https://github.com/ionic-team/ionic/commit/878d7e6))
* **route:** adds route-link ([4a3030f](https://github.com/ionic-team/ionic/commit/4a3030f))
* **router:** reverse lookup with params ([3ce8a67](https://github.com/ionic-team/ionic/commit/3ce8a67))



<a name="0.1.4-2"></a>
## [0.1.4-2](https://github.com/ionic-team/ionic/compare/v0.1.4-0...v0.1.4-2) (2018-03-07)


### Bug Fixes

* **fab:** add side as a property for fab list ([7387d34](https://github.com/ionic-team/ionic/commit/7387d34))
* **ion-router:** fixes routing algorithm ([c8a27b7](https://github.com/ionic-team/ionic/commit/c8a27b7))
* **item:** href ([540c33b](https://github.com/ionic-team/ionic/commit/540c33b))
* **overlays:** bundling of overlays ([9650bec](https://github.com/ionic-team/ionic/commit/9650bec))
* **router:** invalid url ([c7fe694](https://github.com/ionic-team/ionic/commit/c7fe694))
* **routing:** flickering (part 1) ([7b264f9](https://github.com/ionic-team/ionic/commit/7b264f9))
* **tabs:** do not select when using router ([174d9b5](https://github.com/ionic-team/ionic/commit/174d9b5))


### Features

* **router:** adds parameters ([f29e3f4](https://github.com/ionic-team/ionic/commit/f29e3f4))
* **virtual-scroll:** adds JSX support ([dc8b363](https://github.com/ionic-team/ionic/commit/dc8b363))



<a name="0.1.4-1"></a>
## [0.1.4-1](https://github.com/ionic-team/ionic/compare/v0.1.4-0...v0.1.4-1) (2018-03-07)


### Bug Fixes

* **ion-router:** fixes routing algorithm ([c8a27b7](https://github.com/ionic-team/ionic/commit/c8a27b7))
* **overlays:** bundling of overlays ([9650bec](https://github.com/ionic-team/ionic/commit/9650bec))
* **routing:** flickering (part 1) ([7b264f9](https://github.com/ionic-team/ionic/commit/7b264f9))
* **tabs:** do not select when using router ([174d9b5](https://github.com/ionic-team/ionic/commit/174d9b5))


### Features

* **virtual-scroll:** adds JSX support ([dc8b363](https://github.com/ionic-team/ionic/commit/dc8b363))



<a name="0.1.4-0"></a>
## [0.1.4-0](https://github.com/ionic-team/ionic/compare/v0.1.3...v0.1.4-0) (2018-03-06)

### Refactor

- Refactored navigation system

### Bug Fixes

* **testing:** do not throw error for missing Ionic global ([aa91d11](https://github.com/ionic-team/ionic/commit/aa91d11))
* **zone:** forgot to remove console.logs ([4ec3e48](https://github.com/ionic-team/ionic/commit/4ec3e48))



<a name="0.1.3"></a>
## [0.1.3](https://github.com/ionic-team/ionic/compare/v0.1.2...v0.1.3) (2018-03-03)

### Performance Improvements

* Updates to latest stencil, that includes the zone bypassing abilities.

### Bug Fixes

* **ts:** ts strict fixes ([8ff02c7](https://github.com/ionic-team/ionic/commit/8ff02c7))



<a name="0.1.2"></a>
## [0.1.2](https://github.com/ionic-team/ionic/compare/v0.1.1...v0.1.2) (2018-03-03)


### Performance Improvements

* **events:** bypass ngzone ([7366c38](https://github.com/ionic-team/ionic/commit/7366c38))
* **scroll:** watchdog + simplification ([33a6274](https://github.com/ionic-team/ionic/commit/33a6274))


### Bug Fixes

* **scroll:** clearInterval just to be safe ([6da9882](https://github.com/ionic-team/ionic/commit/6da9882))



<a name="0.1.1"></a>
## [0.1.1](https://github.com/ionic-team/ionic/commit/291e85e61128b2f3101d9cea6b42d4cf751dc481) (2018-03-01)


### Bug Fixes

* **button:** pass the property type instead of hardcoding button ([10e481a](https://github.com/ionic-team/ionic/commit/10e481a))



<a name="0.1.0"></a>
## [0.1.0](https://github.com/ionic-team/ionic/commit/43a8c4c7a719169336a84964fc1c737562d764a6) (2018-03-01)
