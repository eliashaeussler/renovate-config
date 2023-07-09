<div align="center">

# Renovate config

[![CGL](https://github.com/eliashaeussler/renovate-config/actions/workflows/cgl.yaml/badge.svg)](https://github.com/eliashaeussler/renovate-config/actions/workflows/cgl.yaml)
[![Release](https://github.com/eliashaeussler/renovate-config/actions/workflows/release.yaml/badge.svg)](https://github.com/eliashaeussler/renovate-config/actions/workflows/release.yaml)
[![License](https://img.shields.io/github/license/eliashaeussler/renovate-config)](LICENSE)

</div>

This package contains basic [Renovate](https://docs.renovatebot.com/) config for
use in my personal projects. It is not meant to be used anywhere else. I won't
provide support and don't accept pull requests for this repo.

## 🚢 Config presets

* [`default.json`](default.json) *– base configuration for all projects*
* [`typo3-extension.json`](typo3-extension.json) *– configuration for [TYPO3 CMS](https://typo3.org/) extensions*

## ⚡ Usage

Add this to your `renovate.json`:

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": [
        "github>eliashaeussler/renovate-config"
    ]
}
```

## ⭐ License

This project is licensed under [GNU General Public License 3.0 (or later)](LICENSE).
