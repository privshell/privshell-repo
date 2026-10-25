# Install guide

This guide explains how to add the PrivShell repository to your root manager, install modules from it and keep them up to date.

## Requirements

- An Android device rooted with **KernelSU**, **KernelSU Next**, **APatch** or **Magisk**
- An app that can load module repositories, such as **MMRL**
- An internet connection for adding the repository and downloading modules

## Repository URL

```
https://privshell.github.io/privshell-repo/json/modules.json
```

## Method 1: MMRL (recommended)

1. Install **MMRL** from its official GitHub releases page and grant it root access.
2. Open the repositories screen in MMRL.
3. Add a new repository and paste the URL above.
4. Return to the module list. The PrivShell modules appear alongside any other repositories you have added.
5. Open a module, review its description and tap **Install**.
6. Reboot when the installer asks you to.

## Method 2: Root manager with repository support

Some root managers can load third-party module repositories directly.

1. Open the manager's module or repository settings.
2. Add the repository URL listed above.
3. Install modules from the list and reboot when prompted.

## Method 3: Manual install from a zip

1. Download the module zip from the module's release page.
2. Open your root manager and choose **Install from storage** (the name varies by manager).
3. Select the zip, wait for the installer to finish and reboot.

## Opening a module's WebUI

All PrivShell modules ship a WebUI.

| Root solution | How to open it |
| --- | --- |
| KernelSU / KernelSU Next | Open the module in the manager and tap the WebUI button. |
| APatch | Open the module in the manager and tap the WebUI button. |
| Magisk | Open the module from a WebUI-capable app such as MMRL. |

## Updating

With the repository added, MMRL lists available updates on the module's page. Install the update and reboot. Modules that ship their own update flow (for example **ORBIT // STORE** for modules from modules.kernelsu.org) can update through their WebUI.

## Uninstalling

Remove the module from your root manager's module list and reboot. Module data stored outside the module folder, such as backups created by **APEX // APPS** or **Git Migrator**, is not removed automatically. Delete it manually if you no longer need it.

## Troubleshooting

**The repository fails to load.**
Open the repository URL in a browser. If you see JSON, the index is reachable and the problem is your network or the app. If the page does not load, try again later or switch networks.

**A module installs but shows no WebUI button.**
Make sure your manager supports module WebUIs. On Magisk, open the WebUI through MMRL or another WebUI-capable app. Reboot once after installing.

**A module does not appear in MMRL after adding the repository.**
Pull to refresh the module list, or remove and re-add the repository. Confirm the URL has no trailing spaces.

**Something stopped working after installing a module.**
Disable the module in your root manager and reboot. Then report the issue using the [issue form](https://github.com/privshell/privshell-repo/issues/new/choose) with the module version, your root solution and your Android version.
