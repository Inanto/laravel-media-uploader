# Release Notes for Laravel Media Uploader
### v8.0.0
* **Fixes**
  - Remove support for BsForm package [2d17c04](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/2d17c04831f52838a7c1bc9157e57940030f81a8)
### v6.3.3
* **Fixes**
  - Run the artisan command once after saving the media instead of running in loop [22](https://github.com/ahmed-aliraqi/laravel-media-uploader/pull/22) by [AbdullahFaqeir](https://github.com/AbdullahFaqeir)
  - Fix base64 validation issue [05fed33](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/05fed333a5b96196cc78b4fa4aa1e533aef4f1e9)
### v6.3.0
* **Added**
  - Add Support for laravel 9.x [18](https://github.com/ahmed-aliraqi/laravel-media-uploader/pull/18) by [AbdullahFaqeir](https://github.com/AbdullahFaqeir)
  ### v6.2.0
* **Fixes**
  - Clean the temporary files every six hours [b132699](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/b1326999f3cac6a548bad11c00cf2d7da0287b0d)
* **Added**
  - Add Uploader helper [4e743bf](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/4e743bfefdcf03e6d9b3e0d05966f2c08e71ddda)
### v6.1.2
* **Fixes**
  - Replace Hindu-Arabic numerals to Arabic numerals [4e45b49](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/4e45b4945a8311eecb53e3fd26062934b43aeea4)
### v6.1.0
* **Added**
  - Optimize and Upload images as base64.
### v6.0.1
* **Fixes**
  - Add ability to filter by collection with token to avoid duplicate the old media.
### v6.0.0
* **Added**
  - Add support for php 8.0
* **Changes**
  - Use `MediaHasBeenAdded` Event instead of `PerformConversionsJob`
  - Bump `laravel media library` from ^8.0 to ^9.0
### v5.1.0
* **Added**
  - Add `AudioComponent` for `laravel-bootstrap-forms`,
  - Add `VideoComponent` for `laravel-bootstrap-forms`,
  - Add `Audioomponent` for `laravel-bootstrap-forms`,
  - Add `Mediaomponent` for `laravel-bootstrap-forms`,
  - Add `_ide_helper.php` file to provide autocomplete information to your IDE.

### v5.0.1
* **Fixes**
    - Keep only configured latest media [4e3f6e6](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/4e3f6e6c4b25797fafa1cae3173e89a93e260339).
### v5.0.0
* **Added**
    - Add `form` and `unlimited` option to form component.
### v4.1.1
* **Fixes**
    - Fix support for laravel 8.x [678f06d](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/678f06d8441c2cbd8923bc3f0c6aa7b831c36f78)
### v4.1.0
* **Added**
    - Add support for laravel 8.x
### v4.0.0
* **Changes**
    - Upgraded media-library to ^8.0. [c7f1e8e](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/c7f1e8eda602d4b377cb33c98cf244c200dd1cf1)
### v3.0.0
* **Changes**
    - change vendor name of laravel-bootstrap-forms. [d09599d](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/d09599d07d8e6ca92f393de0dd0a47cc1c934b32)
### v2.1.0
* **Added**
    - Add "regenerate-after-assigning" option in config file [4fb569b](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/4fb569ba99dafd3098698e4aa274c1868d0d9206)
* **Changes**
    - The first argument of `addAllMediaFromTokens($tokens)` now support `string`, `array`, `null` value. [a451ebb](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/a451ebbdfac6e94ca1c588977a4ada4c489a48bf)
### v2.0.1
* **Fixes**
    - Register and publish translations [b5b7dd3](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/b5b7dd3efd11a6c0c6aeac82e83003da645a1a09)
### v2.0.0
* **Changes**
    - Remove built in migration and use published instead [8611ac6](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/8611ac6bbb9b8833c8231ae8d03e4cf1cb7d6866).
    - Remove `uploader:install` command line [7f0bb58](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/7f0bb58b45f634ba4937ff7cdfee025e8a6e021b).
    - Optional `preview` flag in MediaResource [e16344d](https://github.com/ahmed-aliraqi/laravel-media-uploader/commit/e16344de7eed1fdd33c33186fc4c0b21df23f835).
### v1.0.1
* **Changes**
    - Add tow optional arguments in `addAllMediaFromTokens()`
        - $tokens = []
        - $collection = 'default'
