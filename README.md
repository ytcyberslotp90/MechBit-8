<div align="center">

# 🛡️ MechBit-8 (MB-8)
### Cryptographic Engine

![MB-8 Logo](mb8.png)

[![Build](https://img.shields.io/badge/build-passing-39FF14?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=0d0d0d)](#)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white&labelColor=0d0d0d)](#)
[![KDF Rounds](https://img.shields.io/badge/KDF-2000%20rounds-FF2079?style=for-the-badge&logo=hashnode&logoColor=white&labelColor=0d0d0d)](#)
[![Hash](https://img.shields.io/badge/hash-SHA--256-00BFFF?style=for-the-badge&logo=letsencrypt&logoColor=white&labelColor=0d0d0d)](#)
[![Integrity](https://img.shields.io/badge/integrity-CRC--32-FFD600?style=for-the-badge&logo=verizon&logoColor=white&labelColor=0d0d0d)](#)
[![Engine](https://img.shields.io/badge/engine-RotorChain-A742FF?style=for-the-badge&logo=enigma&logoColor=white&labelColor=0d0d0d)](#)
[![License](https://img.shields.io/badge/license-Proprietary-808080?style=for-the-badge&logo=files&logoColor=white&labelColor=0d0d0d)](#)
[![Status](https://img.shields.io/badge/status-Closed%20Source-critical?style=for-the-badge&logo=lock&logoColor=white&labelColor=0d0d0d)](#)

</div>

---

> ### ⚠️ CRITICAL WARNING
> **DON'T MISUSE THIS. THE CREATOR ISN'T RESPONSIBLE FOR ANY DAMAGES.**
> This tool is deployed strictly for data masking, localized verification, and structural obfuscation evaluation. Any unauthorized deployment, malicious traffic simulation, or damage caused by improper pipeline usage is entirely on the end-user.

---

## 📦 Distribution Manifest

[![Source](https://img.shields.io/badge/source-Closed-red?style=flat-square&logo=github&logoColor=white)](#)
[![Payload](https://img.shields.io/badge/payload-.mb8-39FF14?style=flat-square)](#)

To maintain the architectural integrity and proprietary defense mechanisms of the **MB-8 Engine**, the source infrastructure remains closed. This repository contains only the finalized, compiled runtime deployment components:

* **`mb8.exe`** — The fully armed, standalone Windows console executable compiled via the PyInstaller pipeline. Includes the 2,000-round SHA-256 KDF matrix, shifting `RotorChain` parity machine, and live CRC-32 trailer validation.
* **`example.mb8`** — A pre-encoded, key-seeded target payload showcasing the signature ASCII symbol stream and randomized chaff injection.

---

## ⚡ Quick Start Deployment

[![CLI](https://img.shields.io/badge/interface-CLI-black?style=flat-square&logo=windowsterminal&logoColor=white)](#)
[![Shell](https://img.shields.io/badge/shell-CMD%20%7C%20PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)](#)

Since this is a portable command-line tool, drop `mb8.exe` into your environment directory or local system path and interface with it directly via CMD or PowerShell.

### 1. Test the Decoding Pipeline

Attempt to unwrap the provided example payload using your passphrase:

```bash
mb8.exe --decode --file example.mb8
```

### 2. Test the Encoding Pipeline

Mask a localized text file or configuration string into text-safe symbol static:

```bash
mb8.exe --encode --file example.mb8
```

---

## 🛠️ Core Engine Specs

[![Entropy](https://img.shields.io/badge/entropy-non--linear%20mapping-A742FF?style=flat-square)](#)
[![Stretching](https://img.shields.io/badge/key%20stretching-2000x-FF2079?style=flat-square)](#)
[![CRC](https://img.shields.io/badge/payload%20check-CRC--32-FFD600?style=flat-square)](#)

| Module | Description |
|---|---|
| 🌀 **Entropy Generation** | Shifting integer state parameters (`pos_a`, `pos_b`, `pos_c`) ensuring non-linear token mapping per bit. |
| 🔐 **Brute-Force Mitigation** | Key stretching via an iterative 2,000-round cryptographic hashing block before initialization vectors are bound. |
| ✅ **Integrity Seal** | Appends an automatic hardware-speed cyclic redundancy check to dump corrupted payloads instantly on execution. |

---

<div align="center">

![Made with](https://img.shields.io/badge/made%20with-C%2B%2B%20%7C%20Python-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=0d0d0d)
![Author](https://img.shields.io/badge/author-Cyber%20Slot-39FF14?style=for-the-badge&logo=ghost&logoColor=white&labelColor=0d0d0d)

</div>
