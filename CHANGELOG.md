<a name="1.2.1"></a>
## [1.2.1](https://github.com/videojs/videojs-vr/compare/v1.2.0...v1.2.1) (2018-05-08)

### Bug Fixes

* Correctly show an error in IE/Safari when webvr is unsupported ([#67](https://github.com/videojs/videojs-vr/issues/67)) ([67988da](https://github.com/videojs/videojs-vr/commit/67988da))

<a name="1.2.0"></a>
# [1.2.0](https://github.com/videojs/videojs-vr/compare/v1.1.1...v1.2.0) (2018-03-27)

### Bug Fixes

* chrome m55 android gyro breakage by updating webvr-polyfill ([#64](https://github.com/videojs/videojs-vr/issues/64)) ([ff8e461](https://github.com/videojs/videojs-vr/commit/ff8e461))

### Chores

* **package:** update rollup to version 0.57.1 ([#62](https://github.com/videojs/videojs-vr/issues/62)) ([d81a5a4](https://github.com/videojs/videojs-vr/commit/d81a5a4)), closes [#57](https://github.com/videojs/videojs-vr/issues/57)

<a name="1.1.1"></a>
## [1.1.1](https://github.com/videojs/videojs-vr/compare/v1.1.0...v1.1.1) (2018-02-20)

### Bug Fixes

* expose version correctly ([#51](https://github.com/videojs/videojs-vr/issues/51)) ([dd7adc1](https://github.com/videojs/videojs-vr/commit/dd7adc1))
* **OrbitControls:** no pan, less speed, no zoom ([#52](https://github.com/videojs/videojs-vr/issues/52)) ([44b6d41](https://github.com/videojs/videojs-vr/commit/44b6d41))
* rework three example build, to fix webpack ([#53](https://github.com/videojs/videojs-vr/issues/53)) ([382156b](https://github.com/videojs/videojs-vr/commit/382156b))

<a name="1.1.0"></a>
# [1.1.0](https://github.com/videojs/videojs-vr/compare/v1.0.3...v1.1.0) (2018-01-31)

### Features

* remove threejs files from the repo ([#43](https://github.com/videojs/videojs-vr/issues/43)) ([a5cf671](https://github.com/videojs/videojs-vr/commit/a5cf671))

### Bug Fixes

* default projection typo ([#47](https://github.com/videojs/videojs-vr/issues/47)) ([4c0c7bb](https://github.com/videojs/videojs-vr/commit/4c0c7bb))
* native webvr ([#45](https://github.com/videojs/videojs-vr/issues/45)) ([4b3a89f](https://github.com/videojs/videojs-vr/commit/4b3a89f))
* safari hls ([#48](https://github.com/videojs/videojs-vr/issues/48)) ([7dc2a69](https://github.com/videojs/videojs-vr/commit/7dc2a69))

<a name="1.0.3"></a>
## [1.0.3](https://github.com/videojs/videojs-vr/compare/v1.0.2...v1.0.3) (2017-12-04)

### Bug Fixes

* workaround for firefox/polyfill display issue ([#41](https://github.com/videojs/videojs-vr/issues/41)) ([76e6e03](https://github.com/videojs/videojs-vr/commit/76e6e03))

<a name="1.0.2"></a>
## [1.0.2](https://github.com/videojs/videojs-vr/compare/v1.0.1...v1.0.2) (2017-10-19)

### Bug Fixes

* equirectangular in the readme ([#29](https://github.com/videojs/videojs-vr/issues/29)) ([7dad7a1](https://github.com/videojs/videojs-vr/commit/7dad7a1))
* make stereo modes so actually stereo [#32](https://github.com/videojs/videojs-vr/issues/32) ([#33](https://github.com/videojs/videojs-vr/issues/33)) ([1e06433](https://github.com/videojs/videojs-vr/commit/1e06433))

<a name="1.0.1"></a>
## [1.0.1](https://github.com/videojs/videojs-vr/compare/v1.0.0...v1.0.1) (2017-08-29)

### Bug Fixes

* equirectangular should be equivelent to 360 ([#28](https://github.com/videojs/videojs-vr/issues/28)) ([f0e5422](https://github.com/videojs/videojs-vr/commit/f0e5422))

### Chores

* update README ([#23](https://github.com/videojs/videojs-vr/issues/23)) ([9e54437](https://github.com/videojs/videojs-vr/commit/9e54437))

<a name="1.0.0"></a>
# 1.0.0 (2017-08-24)

### Features

* add an option to force cardboard button ([#20](https://github.com/videojs/videojs-vr/issues/20)) ([1dee5f7](https://github.com/videojs/videojs-vr/commit/1dee5f7))
* expose more of vrs methods ([#10](https://github.com/videojs/videojs-vr/issues/10)) ([3cc1092](https://github.com/videojs/videojs-vr/commit/3cc1092))

### Bug Fixes

* add a cardboard button for native webvr support ([#22](https://github.com/videojs/videojs-vr/issues/22)) ([e946219](https://github.com/videojs/videojs-vr/commit/e946219))
* auto projection should be set to the correct value and not auto ([#4](https://github.com/videojs/videojs-vr/issues/4)) ([377e8a6](https://github.com/videojs/videojs-vr/commit/377e8a6))
* cleanup window listeners ([#15](https://github.com/videojs/videojs-vr/issues/15)) ([d3e45ad](https://github.com/videojs/videojs-vr/commit/d3e45ad))
* correctly check for cardboard button on control bar so we don't add two ([#26](https://github.com/videojs/videojs-vr/issues/26)) ([9184472](https://github.com/videojs/videojs-vr/commit/9184472))
* encode svg in css, use exact button replacement size ([#3](https://github.com/videojs/videojs-vr/issues/3)) ([9a37374](https://github.com/videojs/videojs-vr/commit/9a37374))
* make cardboard button pseudo fullscreen on iOS ([#12](https://github.com/videojs/videojs-vr/issues/12)) ([17a41c0](https://github.com/videojs/videojs-vr/commit/17a41c0))
* pin webvr-polyfill to 0.9.23 ([#21](https://github.com/videojs/videojs-vr/issues/21)) ([a644d1e](https://github.com/videojs/videojs-vr/commit/a644d1e))
* pixelation issues on some devices ([#17](https://github.com/videojs/videojs-vr/issues/17)) ([6f09814](https://github.com/videojs/videojs-vr/commit/6f09814))
* prevent initialization from happening twice ([#9](https://github.com/videojs/videojs-vr/issues/9)) ([33deadc](https://github.com/videojs/videojs-vr/commit/33deadc))
* separate and reset CardboardButton and BigVrPlayButton ([#11](https://github.com/videojs/videojs-vr/issues/11)) ([3ae105e](https://github.com/videojs/videojs-vr/commit/3ae105e))
* use player `fullscreenchange` event so fullscreen toggle works on Safari ([#2](https://github.com/videojs/videojs-vr/issues/2)) ([05c0f23](https://github.com/videojs/videojs-vr/commit/05c0f23))

