# ORBIT // STORE

In-manager module store.

## Overview

ORBIT // STORE brings a module store into your root manager's WebUI. Browse modules from modules.kernelsu.org, install them and keep them updated without leaving the manager. Downloads are verified with sha256 before they are installed.

## Features

- **Browse** the modules listed on modules.kernelsu.org
- **Install and update** modules from inside your root manager
- **sha256 verification** of downloaded modules
- **WebUI-first experience** that works where your manager can open module WebUIs

## Requirements

- Android device rooted with KernelSU, KernelSU Next, APatch or Magisk
- A root manager or app that can open module WebUIs (see the [install guide](INSTALL.md))
- An internet connection

## Installation

1. Add the PrivShell repository to MMRL or your root manager. See the [install guide](INSTALL.md).
2. Install **ORBIT // STORE** and reboot.
3. Open the module's WebUI from your root manager.

## Getting started

1. Open the WebUI and browse or search the module list.
2. Open a module to read its description before installing.
3. Install the module and reboot when your manager asks you to.
4. Return to the store later to check for updates.

## Good to know

- Only install modules you trust. Verification confirms that a download is intact, not that a module is safe.
- Modules are installed through your root manager, so its confirmation prompts and reboot requirements still apply.

## Troubleshooting

**The module list is empty.**
Check your internet connection and reopen the WebUI.

**A download fails verification.**
Do not install it. Try again later, and if the problem persists, report it with the module name.

**The WebUI does not open.**
See the troubleshooting section of the [install guide](INSTALL.md).

## Support

Open an [issue](https://github.com/privshell/privshell-repo/issues/new/choose) and include the module version, your root solution and your Android version.
