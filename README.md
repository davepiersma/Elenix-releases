# Elenix releases

Elenix is a taskbar for Windows 11, made by Vienix. It replaces the Windows taskbar with three floating islands at the bottom of the screen.

This repository only holds the release files. The source code is private.

## What Elenix does

- The left island holds Start and your apps.
- The middle island shows your next appointment from Outlook, and grows into an alert when it starts.
- The right island holds your widgets and the clock.
- Ctrl+K searches your whole PC, including Windows settings.
- Notification rules per app keep the noise down.

## Requirements

Windows 11, 64-bit. No administrator rights are needed.

## Install

Download `Elenix-Setup-<version>.exe` from the [latest release](https://github.com/davepiersma/Elenix-releases/releases/latest) and run it. It installs for your user account.

The file is not signed yet, so Windows SmartScreen may warn. Choose "More info" and then "Run anyway".

## Updates

Elenix checks this repository for a new release about once a day. You can also check yourself in Settings, under About. You can turn the automatic check off there.

Each release lists the SHA-256 of its setup file. Elenix checks that hash before it installs an update. A window shows the progress, and Elenix tells you which version is installed when it is done. Your settings stay as they are.

## Uninstall

Remove Elenix in Windows Settings, under Apps. Elenix asks first. Your settings stay unless you choose to remove them.

## Privacy

Elenix reads your calendar and notifications on your PC only. A widget you add yourself may connect to the internet. The only internet connection is the update check against this repository, and the download when you choose to update.

## Versions

Every version and its changes are listed under [Releases](https://github.com/davepiersma/Elenix-releases/releases).
