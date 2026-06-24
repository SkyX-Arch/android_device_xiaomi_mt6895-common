# MediaTek MT6895 Common Tree

Common device configuration for MediaTek MT6895-based devices.

This repository contains shared platform-specific configuration, policies, and resources used by devices based on the MediaTek MT6895 platform.

## Platform Information

| Item           | Value                       |
| -------------- | --------------------------- |
| Platform       | MediaTek MT6895             |
| Marketing Name | Dimensity 8100 / 8100 Ultra |
| Architecture   | ARM64                       |
| Vendor         | MediaTek                    |

## Purpose

This repository provides common components shared across MT6895-based devices, reducing duplication between device trees and simplifying maintenance.

## Repository Contents

### SELinux

* Platform SEPolicy rules
* File contexts
* Property contexts
* Service contexts
* Vendor compatibility policies

### System Configuration

* Init scripts
* Framework overlays
* Permissions
* System properties
* Feature configuration

### Platform Components

* Power configuration
* Display configuration
* Audio configuration
* Media configuration
* Hardware service integration

### Compatibility Fixes

* Android platform compatibility adjustments
* MediaTek-specific workarounds
* Platform stability improvements
* Security policy updates

## Supported Android Versions

* Android 16

## Used By

* Xiaomi 12T (plato)

## Status

* Actively maintained
* SELinux Enforcing
* Android 16 compatible

## Credits

* [The LineageOS Project](https://github.com/LineageOS)
* [XagaForge](https://github.com/XagaForge)
* [Archcloudy](https://github.com/archcloudy)
* [Xiaomi MT6895 Devs](https://github.com/xiaomi-mt6895-devs)

## Maintainer

SkyX-Arch
