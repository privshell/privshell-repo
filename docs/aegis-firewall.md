# AEGIS // FIREWALL

Kernel-level per-app firewall with a WebUI.

## Overview

AEGIS // FIREWALL lets you decide, app by app, which network paths are allowed. Rules are enforced at the kernel level, so they apply regardless of how an app tries to connect. Everything is configured from a WebUI that opens inside your root manager.

## Features

- **Per-app network rules** for Wi-Fi, mobile data, VPN, LAN and roaming
- **Per-app host rules** to allow or block specific hosts for an individual app
- **Screen-off blocking** to cut network access for selected apps while the display is off
- **Live connections** view to see what your apps are connecting to in real time

## Requirements

- Android device rooted with KernelSU, KernelSU Next, APatch or Magisk
- A root manager or app that can open module WebUIs (see the [install guide](INSTALL.md))

## Installation

1. Add the PrivShell repository to MMRL or your root manager. See the [install guide](INSTALL.md).
2. Install **AEGIS // FIREWALL** and reboot.
3. Open the module's WebUI from your root manager.

## Getting started

1. Open the WebUI and review the app list.
2. Choose an app and set its rules for Wi-Fi, mobile data, VPN, LAN and roaming.
3. Add host rules for apps that need finer control.
4. Enable screen-off blocking for apps that should stay silent in the background.
5. Use the live connections view to confirm that your rules behave as expected.

## Good to know

- Start with a few apps rather than blocking everything at once, then widen the rules as you confirm nothing breaks.
- Blocking system components such as push services or the captive portal checker can affect notifications and Wi-Fi sign-in pages.
- Disabling the module in your root manager and rebooting removes all enforcement.

## Troubleshooting

**An app still connects after I blocked it.**
Check which network type it is using in the live connections view and make sure that type is blocked. VPN and LAN traffic have their own rules.

**Notifications stopped arriving.**
Review the rules for your messaging apps and any push-related system services, then allow them again.

**The WebUI does not open.**
See the troubleshooting section of the [install guide](INSTALL.md).

## Support

Open an [issue](https://github.com/privshell/privshell-repo/issues/new/choose) and include the module version, your root solution and your Android version.
