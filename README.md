# 📱ReLumia
The ultimate archive of emergency files, FFUs, tools, and resurrection utilities for Microsoft/Nokia Lumia devices.

⚠️ "You bricked it, we fixed it. Probably."

## ❓ What is ReLumia?
ReLumia is a massive, community-driven archive designed to preserve, restore, and revive Lumia phones — whether you're trying to fix a soft-brick, recover from a bad flash, or just need access to original firmware and tools.

No more digging through dead forums, broken links, or Russian file hosts. It's all here — in one place. Permanently.

## 📦 What's Inside
Here's a breakdown of what's included in this repo (and its releases):

### 🧱 Emergency Files
Hex & Qualcomm emergency boot files for various models

Partition layouts

Test Mode triggers / button combos

USB drivers & recovery identifiers

### 🔄 FFUs (Full Flash Update Images)
Official stock FFUs per Lumia model

Multiple firmware versions (where possible)

Sorted by device name, codename, and firmware version

Includes both retail and care firmware images

### 💻 Software Tools
Windows Device Recovery Tool (WDRT) – Original installer & latest version

Nokia Care Suite – Product Support Tool (PST) for legacy flashing

Thor2 CLI – For manual FFU flashing

Interop Tools – For the curious hackers

USB & Qualcomm driver packages

## ✅ Supported Devices
Nearly all mainstream Lumia devices are covered, including:

Lumia 520, 521, 525

Lumia 620, 625, 630, 635, 640, 650

Lumia 710, 720, 735, 810, 820, 830

Lumia 920, 925, 928, 930

Lumia 950 / 950 XL

and many more...

Note: Some rare carrier-specific models may still be missing. Contributions are welcome.

## 🛠 Usage Guide
🧠 TL;DR: Flash FFUs with WDRT or Thor2. Use emergency files if you're hard-bricked.

Identify your device
Look at the label under the SIM tray or use thor2 -mode rnd -readdevicerndinfo if semi-alive.

Install drivers & tools
Run the included WDRT or manually install the Lumia USB drivers.

### Flash using Thor2 (advanced)

css
Copy
Edit
thor2 -mode uefiflash -ffufile [your.ffu] -deviceplatformid [ID]
Use emergency files if bricked
Put your Lumia in Emergency Download Mode (EDL) and use the .hex or .mbn files with QFIL or Thor2.

## 📥 Downloads
Most files are too large for GitHub itself. Check the Releases tab or our external mirror for downloads.

## 🧠 FAQ
Q: My phone isn't detected by WDRT. Now what?
A: Use the emergency files to revive it into a flashable state.

Q: Can I downgrade to Windows Phone 8.1?
A: On most models, yes — as long as Secure Boot and UEFI allow it.

Q: Is this legal?
A: Firmware images are provided for archival and recovery purposes. You're responsible for how you use them.

## 🤝 Contributing
Got a rare FFU? A driver package we missed? PRs are open. Fork, contribute, or just drop a file request in Issues.

## ⚰️ Why This Exists
Microsoft may have moved on. The forums may have gone dark. But we haven't forgotten these phones.

This project exists to keep Lumia alive — whether you're a hacker, collector, archivist, or just trying to fix mom's old 640.

## 🧨 Disclaimer
We are not responsible for any damage, bricking, or nuclear fallout caused by files in this repo. Flash at your own risk.

## 📡 Connect
Main repo: github.com/yourusername/ReLumia

Mirror (if any): [yourlinkhere]

DM for questions: @avxadvanced

