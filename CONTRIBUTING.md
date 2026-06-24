# Contributing

Thank you for your interest in contributing to the MT6895 common tree.

This repository contains shared platform components used by MT6895-based devices. Changes made here may affect multiple devices and should be reviewed carefully.

## Before Submitting Changes

Please ensure that:

* The change is platform-wide and not device-specific
* The change has been tested whenever possible
* No regressions have been introduced
* Android compatibility has been considered

Device-specific fixes should generally be submitted to the appropriate device tree instead of this repository.

## Pull Requests

When submitting a pull request:

* Clearly explain the purpose of the change
* Describe potential impact on MT6895 devices
* Keep commits focused and easy to review
* Include testing information when available

Examples of acceptable contributions:

* SELinux policy improvements
* Platform compatibility fixes
* Shared configuration improvements
* Android version bring-up changes
* Common framework adjustments
* Stability and security improvements

## Bug Reports

When reporting an issue, please provide:

* Affected device(s)
* Android version
* Build date
* Relevant logs
* Reproduction steps

Issues lacking sufficient information may be difficult to investigate.

## Notes

Changes affecting common components may have consequences across multiple devices. Please verify changes carefully before submission.

## Maintainer

SkyX-Arch
