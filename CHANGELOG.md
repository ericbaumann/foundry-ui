## [1.0.5](https://github.com/Headstorm/foundry-ui/compare/v1.0.4...v1.0.5) (2021-06-29)


### Bug Fixes

* fix interaction animation bounds when elevation <= 0 ([8fe84ef](https://github.com/Headstorm/foundry-ui/commit/8fe84efd4575fa3b750e60ee6a4b2738f6152f71)), closes [#233](https://github.com/Headstorm/foundry-ui/issues/233)

## [1.0.4](https://github.com/Headstorm/foundry-ui/compare/v1.0.3...v1.0.4) (2021-03-12)


### Bug Fixes

* **interactionfeedback.tsx:** update useResizeObserver in accordance with breaking change ([417598e](https://github.com/Headstorm/foundry-ui/commit/417598eb90f06292a78612052bbbcc74a4283f9c))

## [1.0.3](https://github.com/Headstorm/foundry-ui/compare/v1.0.2...v1.0.3) (2021-03-04)


### Bug Fixes

* 🐛 Scroll position now persists when open/closing options ([5cc4e85](https://github.com/Headstorm/foundry-ui/commit/5cc4e8547aa0c82094ace8167b0b0a6f851e1a87)), closes [#214](https://github.com/Headstorm/foundry-ui/issues/214)

## [1.0.2](https://github.com/Headstorm/foundry-ui/compare/v1.0.1...v1.0.2) (2020-10-19)


### Bug Fixes

* **dropdown:** merge valueItemContainerProps more intelligently ([74625e7](https://github.com/Headstorm/foundry-ui/commit/74625e7fb531532f320e1ff0a48760926d4ddef7)), closes [#202](https://github.com/Headstorm/foundry-ui/issues/202)


### Performance Improvements

* move more dependencies to devDependencies to improve experience while using Foundry UI ([91c3ac6](https://github.com/Headstorm/foundry-ui/commit/91c3ac603b6f326d57231f93d2ac68d7e691cc32))

## [1.0.1](https://github.com/Headstorm/foundry-ui/compare/v1.0.0...v1.0.1) (2020-10-15)


### Bug Fixes

* **image paths:** use absolute paths to github for images and files that are not part of bundle ([80834f3](https://github.com/Headstorm/foundry-ui/commit/80834f3b5ab4c568c9c9b3a61b3a9eca69d59b1a))

# [1.0.0](https://github.com/Headstorm/foundry-ui/compare/v0.1.14...v1.0.0) (2020-10-14)


### Bug Fixes

* **button:** fix feedback position/display superceding buttoncontainer's position/display ([66d3a8f](https://github.com/Headstorm/foundry-ui/commit/66d3a8fcf44a2729304a916cdeb75517db6108b2))
* **button:** set position: relative to contain the feedbackinteraction ([c81f008](https://github.com/Headstorm/foundry-ui/commit/c81f008720726c8fd29d1aa65472d27e39facadd))
* **button:** tweak margin of icon containers ([7f85160](https://github.com/Headstorm/foundry-ui/commit/7f85160a815e052dd5f1ba0955f552fd3cf27a50))
* **button and interactionfeedback:** style the InteractionFeedback for the Button to inline-block ([acf5389](https://github.com/Headstorm/foundry-ui/commit/acf53897cb5ef2f7172ee6ff942c5bd970fd571a))
* **button icon container:** add ability to style icon containers ([5755755](https://github.com/Headstorm/foundry-ui/commit/57557554c88788e5044fde8b42e223604efd1a70))
* **card:** header padding equal on all side if body and footer not present ([64e0c0b](https://github.com/Headstorm/foundry-ui/commit/64e0c0bbd46ef6732f375755b41ab9934f801757))
* **dropdown placeholder and onclear:** demostrate styledplaceholder and fix onclear ([ce237c5](https://github.com/Headstorm/foundry-ui/commit/ce237c5d7a78121d526527ad2d8b6350ceac43a3))
* **dropdown valuecontainer:** rename modalisopen prop to isopen ([89b98e8](https://github.com/Headstorm/foundry-ui/commit/89b98e8b81938ecefac518091a5c3b43867fc8ec))
* **package.json:** install react-portal types ([9f7e2cc](https://github.com/Headstorm/foundry-ui/commit/9f7e2cccaba11b38f2a8c9c7d46e4529df63da87))
* **table:** remove row height of 100% ([1d10f24](https://github.com/Headstorm/foundry-ui/commit/1d10f24294873fd6b9145efd198efe9cce527d1c))
* **textinput:** fix text input charCounter not appearing at the top w/ no error message ([4f31ea2](https://github.com/Headstorm/foundry-ui/commit/4f31ea2ed9b460ae406aee59138a7a36f2b77a5e))
* **textinput:** spread the rest of the props onto the Input element ([856f6cb](https://github.com/Headstorm/foundry-ui/commit/856f6cb5804b1c265c790b8649a94ee1e2550fae))
* **textinput accepts styledtextarea:** textinput accepts styledtextarea ([9b2d106](https://github.com/Headstorm/foundry-ui/commit/9b2d10632af10be2a8a0c509cee34c5bbfd72cdd))
* **uncontrolled ability:** allows component to be uncontrolled as well controlled ([8afbd40](https://github.com/Headstorm/foundry-ui/commit/8afbd407174ecb49e72550171e8656661916a160))
* **update snapshots:** update snapshots again ([f3754e9](https://github.com/Headstorm/foundry-ui/commit/f3754e99f127614a3cd9f218ad02d32a1c9bff68))


### Features

* **button, interactionfeedback:** add InteractionFeedback wrapper around Button ([26cf13d](https://github.com/Headstorm/foundry-ui/commit/26cf13da518827176d696842ea79e6e67a1d2447))
* **button, textinput, checkbox:** add disabled prop ([374355d](https://github.com/Headstorm/foundry-ui/commit/374355d8d8c30dc42d516ec53c1fcbce58e19210))
* **card:** add interaction feedback ([946f907](https://github.com/Headstorm/foundry-ui/commit/946f9071f6837cb4b8ae4103a2e814e302b8d490))
* **card:** streamline Card Feedback API and DOM structure ([dc7535b](https://github.com/Headstorm/foundry-ui/commit/dc7535bd1306f92e284e00d848677c07ceabdd89))
* **docspage props table:** add props table to docspage ([09b124f](https://github.com/Headstorm/foundry-ui/commit/09b124f428fe0971dd7a6dc999c494102f06d112))
* **dropdown:** add value variants using tags ([1aae340](https://github.com/Headstorm/foundry-ui/commit/1aae340ebe8918986c55136ac5b207b84351f22e))
* **dropdown:** add variants to dropdown ([0cc22b3](https://github.com/Headstorm/foundry-ui/commit/0cc22b3978ed9fb51e086adb64c75b44348578fa))
* **enable ripple on buttons by default:** improved the ripple animation and made it the defualt ([f467dbf](https://github.com/Headstorm/foundry-ui/commit/f467dbf400d7c32bbf730b7d2a5c626655986acb))
* **forwardref:** add reference to pass through to component container ([e47f473](https://github.com/Headstorm/foundry-ui/commit/e47f4735b60cde1e41aeaccb74da00a6a592cebe))
* **foundryprovider:** replace useColor hook with generic useTheme hook ([7a13871](https://github.com/Headstorm/foundry-ui/commit/7a13871d65dfbe78e7057d9eb9efad2eb0b335a1))
* **rangeslider:** add functionality to support clicking the RangeSlider's rail to set the value ([beeb2e6](https://github.com/Headstorm/foundry-ui/commit/beeb2e625bd37b3f7d23dea10378adc695ebe3ba))
* **rangeslider:** add markers API ([519f096](https://github.com/Headstorm/foundry-ui/commit/519f096712f300ac76ef1675a1dee1ab82b4f07d))
* **rename package:** rename package name from hs-react-ui to foundry-react-ui, same for angular ([ad21895](https://github.com/Headstorm/foundry-ui/commit/ad2189579e62fef02fa297b0fcce22bacb7fcfce))
* **tag:** add new Tag component ([2fa81a4](https://github.com/Headstorm/foundry-ui/commit/2fa81a42e8f7ad9bdff609382e208e5020ab63b8))
* **textinput:** add character counter and maxlength to textInput ([b45192b](https://github.com/Headstorm/foundry-ui/commit/b45192b11606d8e18afd8abf5661cc51d34a6b2b))
* **v1 release:** commitizen push to trigger a release of v1.0.0 ([791bffa](https://github.com/Headstorm/foundry-ui/commit/791bffa9c0df6b913ba57deaac9a5a54dd9a87fe))
* 🎸 Added slick animation on modal mount ([54fd551](https://github.com/Headstorm/foundry-ui/commit/54fd5519703e49fb42a6b23ce1d1588f040fa894))


### BREAKING CHANGES

* **foundryprovider:** Removed the useColors function

# [1.0.0-v1-release.23](https://github.com/Headstorm/foundry-ui/compare/v1.0.0-v1-release.22...v1.0.0-v1-release.23) (2020-10-14)


### Bug Fixes

* **uncontrolled ability:** allows component to be uncontrolled as well controlled ([8afbd40](https://github.com/Headstorm/foundry-ui/commit/8afbd407174ecb49e72550171e8656661916a160))


### Features

* **forwardref:** add reference to pass through to component container ([e47f473](https://github.com/Headstorm/foundry-ui/commit/e47f4735b60cde1e41aeaccb74da00a6a592cebe))
* **rename package:** rename package name from hs-react-ui to foundry-react-ui, same for angular ([ad21895](https://github.com/Headstorm/foundry-ui/commit/ad2189579e62fef02fa297b0fcce22bacb7fcfce))

# [1.0.0-v1-release.22](https://github.com/Headstorm/foundry-ui/compare/v1.0.0-v1-release.21...v1.0.0-v1-release.22) (2020-09-28)


### Bug Fixes

* **card:** header padding equal on all side if body and footer not present ([64e0c0b](https://github.com/Headstorm/foundry-ui/commit/64e0c0bbd46ef6732f375755b41ab9934f801757))
* **dropdown placeholder and onclear:** demostrate styledplaceholder and fix onclear ([ce237c5](https://github.com/Headstorm/foundry-ui/commit/ce237c5d7a78121d526527ad2d8b6350ceac43a3))

# [1.0.0-v1-release.21](https://github.com/Headstorm/foundry-ui/compare/v1.0.0-v1-release.20...v1.0.0-v1-release.21) (2020-09-28)


### Bug Fixes

* **dropdown valuecontainer:** rename modalisopen prop to isopen ([89b98e8](https://github.com/Headstorm/foundry-ui/commit/89b98e8b81938ecefac518091a5c3b43867fc8ec))

# [1.0.0-v1-release.20](https://github.com/Headstorm/foundry-ui/compare/v1.0.0-v1-release.19...v1.0.0-v1-release.20) (2020-09-22)


### Bug Fixes

* **button:** tweak margin of icon containers ([7f85160](https://github.com/Headstorm/foundry-ui/commit/7f85160a815e052dd5f1ba0955f552fd3cf27a50))
* **button icon container:** add ability to style icon containers ([5755755](https://github.com/Headstorm/foundry-ui/commit/57557554c88788e5044fde8b42e223604efd1a70))
* **textinput accepts styledtextarea:** textinput accepts styledtextarea ([9b2d106](https://github.com/Headstorm/foundry-ui/commit/9b2d10632af10be2a8a0c509cee34c5bbfd72cdd))

# [1.0.0-v1-release.19](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.18...v1.0.0-v1-release.19) (2020-09-01)


### Features

* **card:** streamline Card Feedback API and DOM structure ([dc7535b](https://github.com/Headstorm/rasa-ui/commit/dc7535bd1306f92e284e00d848677c07ceabdd89))

# [1.0.0-v1-release.18](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.17...v1.0.0-v1-release.18) (2020-08-26)


### Bug Fixes

* **button:** set position: relative to contain the feedbackinteraction ([c81f008](https://github.com/Headstorm/rasa-ui/commit/c81f008720726c8fd29d1aa65472d27e39facadd))

# [1.0.0-v1-release.17](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.16...v1.0.0-v1-release.17) (2020-08-26)


### Bug Fixes

* **button:** fix feedback position/display superceding buttoncontainer's position/display ([66d3a8f](https://github.com/Headstorm/rasa-ui/commit/66d3a8fcf44a2729304a916cdeb75517db6108b2))

# [1.0.0-v1-release.16](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.15...v1.0.0-v1-release.16) (2020-08-26)


### Features

* **enable ripple on buttons by default:** improved the ripple animation and made it the defualt ([f467dbf](https://github.com/Headstorm/rasa-ui/commit/f467dbf400d7c32bbf730b7d2a5c626655986acb))

# [1.0.0-v1-release.15](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.14...v1.0.0-v1-release.15) (2020-08-26)


### Bug Fixes

* **button and interactionfeedback:** style the InteractionFeedback for the Button to inline-block ([acf5389](https://github.com/Headstorm/rasa-ui/commit/acf53897cb5ef2f7172ee6ff942c5bd970fd571a))

# [1.0.0-v1-release.14](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.13...v1.0.0-v1-release.14) (2020-08-25)


### Features

* 🎸 Added slick animation on modal mount ([54fd551](https://github.com/Headstorm/rasa-ui/commit/54fd5519703e49fb42a6b23ce1d1588f040fa894))

# [1.0.0-v1-release.13](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.12...v1.0.0-v1-release.13) (2020-08-25)


### Features

* **dropdown:** add value variants using tags ([1aae340](https://github.com/Headstorm/rasa-ui/commit/1aae340ebe8918986c55136ac5b207b84351f22e))

# [1.0.0-v1-release.12](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.11...v1.0.0-v1-release.12) (2020-08-24)


### Features

* **docspage props table:** add props table to docspage ([09b124f](https://github.com/Headstorm/rasa-ui/commit/09b124f428fe0971dd7a6dc999c494102f06d112))

# [1.0.0-v1-release.11](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.10...v1.0.0-v1-release.11) (2020-08-21)


### Bug Fixes

* **textinput:** spread the rest of the props onto the Input element ([856f6cb](https://github.com/Headstorm/rasa-ui/commit/856f6cb5804b1c265c790b8649a94ee1e2550fae))

# [1.0.0-v1-release.10](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.9...v1.0.0-v1-release.10) (2020-08-20)


### Features

* **card:** add interaction feedback ([946f907](https://github.com/Headstorm/rasa-ui/commit/946f9071f6837cb4b8ae4103a2e814e302b8d490))

# [1.0.0-v1-release.9](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.8...v1.0.0-v1-release.9) (2020-08-20)


### Features

* **button, interactionfeedback:** add InteractionFeedback wrapper around Button ([26cf13d](https://github.com/Headstorm/rasa-ui/commit/26cf13da518827176d696842ea79e6e67a1d2447))

# [1.0.0-v1-release.8](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.7...v1.0.0-v1-release.8) (2020-08-19)


### Features

* **rangeslider:** add markers API ([519f096](https://github.com/Headstorm/rasa-ui/commit/519f096712f300ac76ef1675a1dee1ab82b4f07d))

# [1.0.0-v1-release.7](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.6...v1.0.0-v1-release.7) (2020-08-19)


### Bug Fixes

* **textinput:** fix text input charCounter not appearing at the top w/ no error message ([4f31ea2](https://github.com/Headstorm/rasa-ui/commit/4f31ea2ed9b460ae406aee59138a7a36f2b77a5e))


### Features

* **dropdown:** add variants to dropdown ([0cc22b3](https://github.com/Headstorm/rasa-ui/commit/0cc22b3978ed9fb51e086adb64c75b44348578fa))

# [1.0.0-v1-release.6](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.5...v1.0.0-v1-release.6) (2020-08-19)


### Features

* **rangeslider:** add functionality to support clicking the RangeSlider's rail to set the value ([beeb2e6](https://github.com/Headstorm/rasa-ui/commit/beeb2e625bd37b3f7d23dea10378adc695ebe3ba))

# [1.0.0-v1-release.5](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.4...v1.0.0-v1-release.5) (2020-08-19)


### Features

* **tag:** add new Tag component ([2fa81a4](https://github.com/Headstorm/rasa-ui/commit/2fa81a42e8f7ad9bdff609382e208e5020ab63b8))

# [1.0.0-v1-release.4](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.3...v1.0.0-v1-release.4) (2020-08-19)


### Bug Fixes

* **table:** remove row height of 100% ([1d10f24](https://github.com/Headstorm/rasa-ui/commit/1d10f24294873fd6b9145efd198efe9cce527d1c))

# [1.0.0-v1-release.3](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.2...v1.0.0-v1-release.3) (2020-08-18)


### Features

* **foundryprovider:** replace useColor hook with generic useTheme hook ([7a13871](https://github.com/Headstorm/rasa-ui/commit/7a13871d65dfbe78e7057d9eb9efad2eb0b335a1))


### BREAKING CHANGES

* **foundryprovider:** Removed the useColors function

# [1.0.0-v1-release.2](https://github.com/Headstorm/rasa-ui/compare/v1.0.0-v1-release.1...v1.0.0-v1-release.2) (2020-08-17)


### Features

* **textinput:** add character counter and maxlength to textInput ([b45192b](https://github.com/Headstorm/rasa-ui/commit/b45192b11606d8e18afd8abf5661cc51d34a6b2b))

# [1.0.0-v1-release.1](https://github.com/Headstorm/rasa-ui/compare/v0.1.0-v1-release.1...v1.0.0-v1-release.1) (2020-08-14)


### Features

* **button, textinput, checkbox:** add disabled prop ([374355d](https://github.com/Headstorm/rasa-ui/commit/374355d8d8c30dc42d516ec53c1fcbce58e19210))

# [0.1.0-v1-release.1](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0-v1-release.1) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))

# [0.1.0](https://github.com/Headstorm/rasa-ui/compare/v0.0.8...v0.1.0) (2020-08-11)


### Features

* **cicd:** add cicd through github actions ([34a8fc0](https://github.com/Headstorm/rasa-ui/commit/34a8fc0245c335e4ca8fbf16291fc39fda963f64))
* **utils/styles.ts:** move elevation shadow calculation to single function ([3e2332e](https://github.com/Headstorm/rasa-ui/commit/3e2332e64b50320681dded46e24562ff29b7bb49))
