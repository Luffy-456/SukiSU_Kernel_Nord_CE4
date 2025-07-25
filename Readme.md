## Useful Links

[![Static Badge](https://img.shields.io/badge/Kernel%20Manifest%20for%20OnePlus%20Nord%20CE%204-EB0029?style=for-the-badge&logo=OnePlus)](https://github.com/OnePlusOSS/kernel_manifest/tree/oneplus/sm7550)
[![Static Badge](https://img.shields.io/badge/LuffyOP%20Updates-Telegram-blue?style=for-the-badge&logo=Telegram)](https://t.me/luffyop_updates)
[![Static Badge](https://img.shields.io/badge/OnePlusNordCE4%20Updates-Telegram-blue?style=for-the-badge&logo=Telegram)](https://t.me/oneplus_nordce4)

------

## Requirements

* Bootloader Unlocked 🔓
* **5.15.149 Kernel based**
* To verify for which OxygenOS version you can flash, **check the release notes of the respective kernel**
* Working Brain 🧠

------

## Required Modules

* [Susfs Module](https://github.com/sidex15/susfs4ksu-module/releases)
* To use ZRAM, download the module from your respective kernel release section (**must read each kernel’s caution/note**)

------

# How To

### Flash Kernel

* Use [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher/releases)

### Update Your Device Without Losing Root Access

#### Method 1: For Magisk or KernelSU (LKM) Users

1. Download the full OTA update for your device.
2. Install the update using Local Update (via your device’s system updater).
3. Before restarting:
   - Open Magisk/KernelSU.
   - Tap "Install" → "Install to Inactive Slot (After OTA)".
4. Once done, return to the updater and tap "Restart".

Your device will reboot with the update applied and root access intact.

#### Method 2: For GKI Kernel Users (Custom Kernel with SUFS)

1. Download the full OTA update.
2. Install the update via Local Update (system updater).
3. Before restarting:
   - Open Kernel Flasher.
   - Flash AnyKernel3 (AK3) to the inactive slot.
   - Do not select any additional options after flashing.
4. Return to the updater and tap "Restart".

Your device will boot into the updated system with your custom kernel and root preserved.

#### Important Notes

- Always back up your data before updating.
- Ensure you’re using the full OTA, not an incremental update.
- If using Magisk Delta or a custom Magisk fork, steps may differ slightly.

------

## Features

<pre> ✅ SukiSU Ultra - ✅ SUSFS  - ✅ VFS HOOK - ✅ Magic Mount Support (KPM) - ✅ BBR Support - ✅ ZRAM </pre>

------

# Thanks To

* [SukiSU](https://github.com/SukiSU-Ultra/SukiSU-Ultra)
* [ZRAM-Module](https://github.com/FurLC/ZRAM-Module)

------

> **PS**: I won't be responsible for anything caused by this. Do at your own risk!
