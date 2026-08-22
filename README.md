<div align="center">

# BROM

**Bannar Robotics Operations Manager**

*Official release & distribution repository*

[![Latest Release](https://img.shields.io/github/v/release/bannar-robotics/BROM?label=latest&style=for-the-badge)](https://github.com/bannar-robotics/BROM/releases/latest)
[![License](https://img.shields.io/badge/license-Proprietary-red?style=for-the-badge)](./LICENSE)
[![Platforms](https://img.shields.io/badge/platforms-Android%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20iOS-blue?style=for-the-badge)](#available-platforms)

### ⬇️ [**DOWNLOAD BROM**](https://github.com/bannar-robotics/BROM/releases/latest) ⬇️

</div>

---

## What is BROM?

BROM (Bannar Robotics Operations Manager) is Bannar Robotics' operations management application, built with Flutter for Android, iOS, Windows, macOS, and Linux.

This repository does **not** contain BROM's source code. It exists solely to distribute official, signed BROM builds and to document releases. The application itself is developed in a private repository.

## Current Version

**Latest release:** `v2.0.0` — see the [Releases page](https://github.com/bannar-robotics/BROM/releases/latest) for release notes and changelog.

## Download BROM

The button above always points to the latest official release. You can also browse all releases and pick a specific version:

➡️ **[github.com/bannar-robotics/BROM/releases](https://github.com/bannar-robotics/BROM/releases)**

## Available Platforms

| Platform | Format | Notes |
|---|---|---|
| Android | `.apk` | Direct install (enable "install from unknown sources") |
| Android | `.aab` | For internal distribution via Google Play only |
| Windows | `.msix` or installer `.exe` | See installation notes below |
| macOS | `.dmg` | Signed & notarized disk image |
| Linux | `.tar.gz` (or `.AppImage` if provided) | See installation notes below |
| iOS | TestFlight / Ad-hoc | Apple does not allow direct `.ipa` sideloading — see below |

## Installation

1. Go to the [Releases page](https://github.com/bannar-robotics/BROM/releases).
2. Download the asset for your platform from the version you want.
3. **Android:** open the downloaded `.apk` and allow installation from this source if prompted.
4. **Windows:** run the `.msix`/installer and follow the prompts. If Windows SmartScreen warns you, this is expected for apps distributed outside the Microsoft Store — verify you downloaded from this official repository before proceeding.
5. **macOS:** open the `.dmg` and drag BROM into Applications.
6. **Linux:** extract the `.tar.gz` and run the BROM executable, or install the `.AppImage` if provided.
7. **iOS:** BROM is distributed via TestFlight or ad-hoc distribution. See the instructions on the latest release page or contact support.

## System Requirements

- **Android:** 8.0 (Oreo) or later
- **iOS:** iOS 15 or later
- **Windows:** Windows 10 (64-bit) or later
- **macOS:** macOS 12 (Monterey) or later
- **Linux:** 64-bit desktop distribution with standard GTK libraries

## Version History

See the full changelog on the [Releases page](https://github.com/bannar-robotics/BROM/releases). Every release includes version notes, platform assets, and a summary of changes.

## Access & Security

Downloading BROM does **not** grant you access to use it. BROM uses a separate, controlled authentication system managed by the Bannar Robotics backend. New users must be authorized by a System Administrator before they can log in. This repository and download page never contain credentials, API keys, or any backend secrets.

## License

BROM is proprietary software. See [LICENSE](./LICENSE) for full terms. Downloading or installing BROM does not transfer any ownership or grant rights beyond those explicitly stated in the license.

## Support / Contact

For access requests, activation issues, or general support, contact your Bannar Robotics System Administrator or reach out at **support@bannarrobotics.example** *(replace with your real support address)*.

---

<div align="center">
<sub>© Bannar Robotics. All rights reserved.</sub>
</div>
