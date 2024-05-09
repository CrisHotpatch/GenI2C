# GenI2C

[![Build Status](https://dev.azure.com/UndefinedSS/GenI2C/_apis/build/status/williambj1.GenI2C?branchName=master)](https://dev.azure.com/UndefinedSS/GenI2C/_build/latest?definitionId=1&branchName=master)
[![Release](https://img.shields.io/github/release/williambj1/GenI2C.svg)](https://github.com/williambj1/GenI2C/releases)
[![Language](https://img.shields.io/github/languages/top/williambj1/GenI2C.svg?color=orange&label=swift)](https://github.com/williambj1/GenI2C)
[![Repo Size](https://img.shields.io/github/repo-size/williambj1/GenI2C.svg?color=blueviolet)](https://github.com/williambj1/GenI2C)
[![Issues](https://img.shields.io/github/issues/williambj1/GenI2C.svg)](https://github.com/williambj1/GenI2C/issues)
[![Testers](https://img.shields.io/badge/Testers-Welcome-brightgreen.svg)](https://github.com/williambj1/GenI2C)

Generate SSDT hotpatches for your Touchable Device and get ready for VoodooI2C! 😜

**[简体中文](https://github.com/williambj1/GenI2C/wiki/Readme-CN)**

## Terms of Use

THIS SOFTWARE IS *NOT* SUPPORTED BY THE VoodooI2C DEVELOPER TEAM

DO NOT REQUEST ANY SUPPORT FROM GITHUB ISSUES IN VoodooI2C OR THE VoodooI2C GITTER CHAT ROOM WITH ANY INFORMATION GENERATED FROM THIS APPLICATION. INFORMATION INCLUDED BUT NOT LIMITED TO SCREENSHOTS, GENERATED PATCHES, SYSTEM LOGS.

Automated patches are not granted to always correct, please open an issue if you descovered a bug, pull requests will be highly appreciated.

This software is released under the [MIT License](/LICENSE)

## Download

👉 [![Release](https://img.shields.io/github/release/williambj1/GenI2C.svg)](https://github.com/williambj1/GenI2C/releases)

## Features

- VoodooI2C Information
  - Loaded Status
  - Attatched Submodules
  - Log Extracting
  - Working Mode (APIC, GPIO, Polling)
  - APIC/GPIO Pin showing

- SSDT Generation
  - Using **External** references to maintain APIC/GPIO Pin Bios injection
  - Generate I2C Bus Speed Patch
  - ~~Generate Skylake I2C Controller Patch~~ (In development🚧)
  - Generate GPIO Pin when manually pinning is required
  - Polling mode patch supported (VoodooI2CHID only)

- Tools
  - ACPI Disassembler

- VoodooI2C Diagnosis
  - Ckeck CPU Generation Support
  - AppleIntelLpssI2C.kext/AppleIntelLpssI2CController.kext blocking detection
  - Check VoodooI2C Status
  - Check Magic Trackpad 2 Simulator Engine Status
  - Analyze VoodooI2C Logs

## Credits

- Bat.bat [(@williambj1)](https://github.com/williambj1) for the idea and the **Visual Basic .Net** part of the project
- DogAndPot [(@DogAndPot)](https://github.com/DogAndPot) for the **Swift** part of the project
- **宪武** for sample SSDTs and theoretical support
- [Alexandred](https://github.com/alexandred) for VoodooI2C [(Full Credits)](https://voodooi2c.github.io/#Credits%20and%20Acknowledgments/Credits%20and%20Acknowledgments)
- Startpenghubingzhou [(@penghubingzhou)](https://github.com/penghubingzhou) for providing theoretical support and his fancy DSDT
- Steve Zheng [(@stevezhengshiqi)](https://github.com/stevezhengshiqi) for testing and bug reporting
- http://patorjk.com for the amazing ASCII Art font `Impossible`

