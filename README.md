
<h1 align="center">
  <br>
  <a href="https://github.com/Niks-chan/PBRP-Builder"><img src="https://raw.githubusercontent.com/shovon668/xda-template/r3/pbrp3-banner-xda.png" alt="Welcome to PitchBlack Recovery Project 👋" width="600"></a>
  <br>
 PitchBlack Recovery Project Builder ✨
  <br>
</h1>

<h4 align="center">The Perfect Android Recovery for your device! PBRP provides the most advanced Open Source Android Recovery to troubleshoot your device on the GO!</h4>


<p align="center">
<a>
  <img alt="Version" src="https://img.shields.io/badge/version-3.1.0-blue.svg?cacheSeconds=2592000" />
  </a>

<a>
  <img alt="Status" src="https://img.shields.io/badge/status-stable-deepgreen.svg" />
  </a>

  <a href="https://t.me/Sunshine_Labs" target="_blank">
    <img alt="chat" src="https://img.shields.io/badge/chat-on--telegram-lightblue.svg" />
  </a>

  <a href="https://t.me/niks_chan">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://github.com/PitchBlackRecoveryProject/android_bootable_recovery/blob/android-9.0/LICENSE" target="_blank">
    <img alt="License: Apache--2.0" src="https://img.shields.io/badge/License-Apache--2.0-yellow.svg" />
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-build">How To build</a> •
  <a href="#download">Download</a> •
  <a href="#follow-me">Follow Me</a> •
  <a href="#credits">Credits</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

<h3 align="center">
  🏠 <a href="https://github.com/Niks-chan/PBRP-Builder">Homepage</a> •
  📥 <a href="https://t.me/dev_niks">Unofficial Devices</a>
</h3>

## Key Features

* Fresh native android like UI
  - New file manager
  - New Icons
  - New Accent
  - New Background
  - New Action Screens
* Universal package flasher (zip, ozip, img etc)
* MIUI OTA Support
* Encryption Support
* PBRP in house tweaks:
  - AVB 2.0 disabler
  - Treble checker disabler
  - Easy logger
* Popular public tools:
  - Magisk Installer & Remover
  - Magisk Recovery
  - SuperSU Installer & Remover
  - System Apps Remover
  - Password Recovery etc

-----

## How To Build

⚙️ Build

```bash
$ Just go to the github actions tab and set up your parameters
````

## Parameter Description
| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `MANIFEST_BRANCH` | Source branch | android-14.0 |
| `DEVICE_TREE` | Device tree address | https://github.com/Niks-chan/pbrp_device_samsung_a51.git |
| `DEVICE_TREE_BRANCH` | Device branch that you want to use for build (typically corresponds to the manifest branch) | pbrp_4.0 |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendor_boot) | recovery |
| `LDCHECK_PATH` | path to your target binary file, ie. | recovery/root/system/bin/qseecomd |
|  | Note: If you are building manually/locally and you want to use ldcheck for checking dependencies, visit [this](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) for guide. |  |

-----

## Download

You can [download](https://github.com/Niks-chan/pbrp_device_samsung_a51) the latest version of my Unofficial PBRP build via [telegram channel](https://t.me/dev_niks) or [github](https://github.com/Niks-chan).

## Follow Me

* GitHub: [@Niks-chan](https://github.com/Niks-chan/)
* Telegram: [@niks_chan](https://t.me/niks_chan)


## Credits

This software uses the following open source project(s):

* [TWRP](https://github.com/minimal-manifest-twrp)


## Support

Give a ⭐️ if this project helped you!

## License

Copyright © 2020 [PitchBlack Recovery Project](https://github.com/PitchBlackRecoveryProject).<br />
This project is [Apache 2.0](https://github.com/PitchBlackRecoveryProject/android_bootable_recovery/blob/android-9.0/LICENSE) licensed.

***
> [PitchBlack Recovery Project Team]()