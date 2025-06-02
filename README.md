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
Most Lumias from Windows Phone 8 and above are and will be supported. 
Note: Some rare carrier-specific models may still be missing. Contributions are welcome.

RM-820,
RM-821,
RM-824,
RM-825,
RM-846,
RM-860,
RM-867,
RM-875,
RM-876,
RM-877,
RM-885,
RM-887,
RM-892,
RM-910,
RM-913,
RM-914,
RM-915,
RM-917,
RM-927,
RM-937,
RM-938,
RM-939,
RM-940,
RM-941,
RM-942,
RM-955,
RM-974,
RM-975,
RM-976,
RM-977,
RM-978,
RM-979,
RM-983,
RM-984,
RM-985,
RM-994,
RM-995,
RM-996,
RM-997,
RM-998,
RM-1010,
RM-1017,
RM-1018,
RM-1019,
RM-1020,
RM-1027,
RM-1031,
RM-1032,
RM-1034,
RM-1038,
RM-1039,
RM-1040,
RM-1041,
RM-1045,
RM-1049,
RM-1062,
RM-1063,
RM-1064,
RM-1065,
RM-1066,
RM-1067,
RM-1068,
RM-1069,
RM-1070,
RM-1071,
RM-1072,
RM-1073,
RM-1074,
RM-1075,
RM-1077,
RM-1078,
RM-1085,
RM-1087,
RM-1089,
RM-1090,
RM-1091,
RM-1092,
RM-1096,
RM-1099,
RM-1104,
RM-1105,
RM-1109,
RM-1113,
RM-1114,
RM-1115,
RM-1116,
RM-1118,
RM-1127,
RM-1128,
RM-1140,
RM-1141,
RM-1150,
RM-1152,
RM-1154,

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

