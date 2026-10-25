# Git Migrator

AMOLED WebUI for backing up and moving GitHub repositories.

## Overview

Git Migrator helps you look after your GitHub projects. Back up your repositories, move them to a new account with all branches, tags and history intact, upload folders as new repositories and repair links that still point to your old username. The interface is a dark AMOLED WebUI that opens inside your root manager.

## Features

- **Repository backup** to keep local copies of your GitHub repositories
- **Account migration** that moves repositories with all branches, tags and history
- **Folder upload** to publish a local folder as a repository
- **Link fixer** that updates references to your old username

## Requirements

- Android device rooted with KernelSU, KernelSU Next, APatch or Magisk
- A root manager or app that can open module WebUIs (see the [install guide](INSTALL.md))
- **Termux** with `git` and `python` installed
- An internet connection

## Installation

1. Install Termux and set up the required packages:

   ```sh
   pkg update
   pkg install git python
   ```

2. Add the PrivShell repository to MMRL or your root manager. See the [install guide](INSTALL.md).
3. Install **Git Migrator** and reboot.
4. Open the module's WebUI from your root manager.

## Getting started

1. Open the WebUI and sign in with the credentials it asks for.
2. Run a backup of the repositories you plan to move.
3. Choose the target account and start the migration.
4. Use the link fixer to update references to your old username.
5. Check the new repositories on GitHub before deleting anything from the old account.

## Good to know

- Migrations act on your GitHub account. Use credentials with only the permissions required, and revoke them when you are finished.
- Always keep a backup before moving or deleting repositories.
- Large repositories take longer to back up and transfer. Keep the device charged and connected.

## Troubleshooting

**The WebUI reports that git or python is missing.**
Open Termux and run `pkg install git python`, then reopen the WebUI.

**A migration stops part way.**
Check your connection and your GitHub permissions, then start the migration again for the remaining repositories.

**The WebUI does not open.**
See the troubleshooting section of the [install guide](INSTALL.md).

## Support

Open an [issue](https://github.com/privshell/privshell-repo/issues/new/choose) and include the module version, your root solution and your Android version.
