# Marmaduke Chromium (Homebrew Tap)

*Forked from [cpbotha/homebrew-marmaduke-chromium](https://github.com/cpbotha/homebrew-marmaduke-chromium).*

All Chromium releases can be found at [Woolyss](https://chromium.woolyss.com).
Builds are pulled from [macchrome/macstable](https://github.com/macchrome/macstable).

![](https://github.com/mtslzr/marmaduke-chromium/workflows/Test/badge.svg)

**Current Versions**

![](https://img.shields.io/badge/marmaduke--chromium-100.0.4896.60%20(972766)-blue)

![](https://img.shields.io/badge/marmaduke--chromium--nosync-84.0.4147.89%20(768962)-lightblue)

![](https://img.shields.io/badge/marmaduke--chromium--ungoogled-99.0.4844.84%20(1060)-yellow)

## Installation

```bash
brew tap mtslzr/marmaduke-chromium
brew update
brew install marmaduke-chromium
```

## Casks

This tap includes three versions of Marmaduke Chromium:

`marmaduke-chromium` - Includes Google Sync and wildvine (DRM for Netflix).

`marmaduke-chromium-nosync` - Does not include Google Sync nor wildvine.

`marmaduke-chromium-ungoogled` - ungoogled-chromium ([Eloston/ungoogled-chromium/](https://github.com/Eloston/ungoogled-chromium/))

If you're unsure, you most likely want to install `marmaduke-chromium`.

## Removal

```bash
brew uninstall marmaduke-chromium
brew untap mtslzr/marmaduke-chromium
```

## macOS / "The App Can't Be Opened"

As is the case with numerous Homebrew packages, macOS will warn the first time you open Chromium after an install/update.

For more information, see [here](https://github.com/Homebrew/homebrew-cask/blob/master/doc/faq/app_cant_be_opened.md).

## Updates

If you notice a missing update, please [reach out](mailto:m@tthewsalazar.com) or open a merge request. Thanks!
