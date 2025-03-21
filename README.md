# Marmaduke Chromium (Homebrew Tap)

*Forked from [mtslzr/homebrew-marmaduke-chromium](https://github.com/mtslzr/homebrew-marmaduke-chromium).*

All Chromium releases can be found at [Woolyss](https://chromium.woolyss.com).
Builds are pulled from [macchrome/macstable](https://github.com/macchrome/macstable).

<!-- ![](https://github.com/methbkts/marmaduke-chromium/workflows/Test/badge.svg) -->

**Current Versions**

![](https://img.shields.io/badge/marmaduke--chromium-127.6533.61-blue)

<!-- ![](https://img.shields.io/badge/marmaduke--chromium--nosync-84.0.4147.89-lightblue) -->

![](https://img.shields.io/badge/marmaduke--chromium--ungoogled-134.6998.116-yellow)

## Installation

```bash
brew tap methbkts/marmaduke-chromium
brew update
brew install marmaduke-chromium # or brew install marmaduke-chromium-ungoogled
```

## Casks

This tap includes the following versions of Marmaduke Chromium:

`marmaduke-chromium` - Includes Google Sync and widevine (DRM for Netflix).

<!-- `marmaduke-chromium-nosync` - Does not include Google Sync nor widevine. -->

`marmaduke-chromium-ungoogled` - ungoogled-chromium ([Eloston/ungoogled-chromium/](https://github.com/Eloston/ungoogled-chromium/))

## Removal

```bash
brew uninstall marmaduke-chromium # or brew uninstall marmaduke-chromium-ungoogled
brew untap methbkts/marmaduke-chromium
```

## macOS / "The App Can't Be Opened"

As is the case with numerous Homebrew packages, macOS will warn the first time you open Chromium after an install/update.

For more information, see [here](https://docs.brew.sh/FAQ#why-cant-i-open-a-mac-app-from-an-unidentified-developer).

## Updates

If you notice a missing update, please open a merge request. Thanks!
