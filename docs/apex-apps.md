# APEX // APPS

App manager with a WebUI.

## Overview

APEX // APPS gives you control over what is installed and running on your device. Review preinstalled apps, disable the ones you do not need, and restore them from a snapshot if something goes wrong. Everything is managed from a WebUI that opens inside your root manager.

## Features

- **Preinstalled app review** with the ability to disable apps you do not use
- **Snapshot restore** to bring disabled apps back to a previous state
- **App freezing** to stop apps without uninstalling them
- **Background permission control** to limit what apps may do while you are not using them
- **App data backup** to keep a copy of an app's data
- **Battery policy tuning** to adjust how apps are treated by power management

## Requirements

- Android device rooted with KernelSU, KernelSU Next, APatch or Magisk
- A root manager or app that can open module WebUIs (see the [install guide](INSTALL.md))

## Installation

1. Add the PrivShell repository to MMRL or your root manager. See the [install guide](INSTALL.md).
2. Install **APEX // APPS** and reboot.
3. Open the module's WebUI from your root manager.

## Getting started

1. Create a snapshot before changing anything, so you can always return to the current state.
2. Browse the preinstalled apps and disable the ones you do not need.
3. Freeze apps you rarely use instead of removing them.
4. Adjust background permissions and battery policy for apps that drain power.
5. Back up data for apps you care about before making larger changes.

## Good to know

- Some preinstalled apps are required by the system, the dialer, messaging or push notifications. If you are unsure what an app does, leave it enabled.
- Restoring a snapshot returns app states to what they were when the snapshot was taken.
- Backups are stored on your device. Copy them somewhere safe if they matter to you.

## Troubleshooting

**The device behaves oddly after disabling an app.**
Restore your latest snapshot from the WebUI. If the WebUI is unavailable, disable the module and reboot.

**A frozen app does not start.**
Unfreeze it in the WebUI and open it again.

**The WebUI does not open.**
See the troubleshooting section of the [install guide](INSTALL.md).

## Support

Open an [issue](https://github.com/privshell/privshell-repo/issues/new/choose) and include the module version, your root solution and your Android version.
