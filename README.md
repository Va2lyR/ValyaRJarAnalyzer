# Jar Analyzer

<p align="center">
  <b>Minecraft JAR Analyzer & Cheat Detection Tool</b>
  <br>
  Built for <b>SSers</b> and Minecraft Server Staff
</p>

<p align="center">
  <a href="../../releases">
    <img src="https://img.shields.io/badge/Download-Releases-8B0000?style=for-the-badge" alt="Download">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-8B0000?style=for-the-badge" alt="Windows">
  <img src="https://img.shields.io/badge/Architecture-x64-8B0000?style=for-the-badge" alt="x64">
</p>

<p align="center">
  <b>Developed by ValyaR</b> · Discord: <code>_iaec</code>
</p>

---

## About

**Jar Analyzer** is a Minecraft **SSing tool** designed for **SSers (Screen Sharers)** and server staff who need to inspect a player's JAR files during a screen share.

It analyzes JAR files for known cheat signatures, ghost clients, suspicious code, obfuscation indicators, and other findings that may require further investigation.

> Built as a tool for Minecraft server security, SSing, and cheat investigation.

---

## Features

### 🔍 Deep JAR Analysis

* Constant-pool analysis
* Class inspection
* Nested-JAR inspection
* Manifest analysis
* Archive-structure analysis
* Suspicious file detection
* Scan JARs across available drives

### 🧬 Cheat Detection

Detects indicators associated with:

* Combat cheats
* Movement cheats
* Render modifications
* Bypass modules
* Ghost clients
* Cheat frameworks
* Suspicious mixins
* Obfuscation markers
* Known cheat signatures

### ⚖️ Weighted Detection

Every signature has a weight from **1–4**.

Multiple findings are combined to determine the final verdict.

| Verdict           | Meaning                   |
| :---------------- | :------------------------ |
| 🟢 **Clean**      | No significant findings   |
| 🔵 **Notable**    | Weak indicators           |
| 🟡 **Suspicious** | Requires investigation    |
| 🟠 **Detected**   | Strong cheat indicators   |
| 🔴 **Critical**   | Strong cheat/family match |
| ⚫ **Unreadable**  | JAR could not be analyzed |

### 🕵️ Behavioral Detection

Detects suspicious combinations and behaviors such as:

* Agent injection indicators
* String decryptors
* Self-destruct routines
* Hollow-shell patterns
* Suspicious class combinations

### 💻 Built-in Decompiler

Includes a **CFR-powered decompiler** for deeper SS investigation.

Features include:

* Source-code viewing
* Code search
* Themes
* HTML export

### 🌍 Bilingual UI

* 🇺🇸 English
* 🇸🇦 العربية

### 📦 Portable

* Single `.exe`
* No Java installation required
* No .NET installation required
* Windows 10/11 x64

---

## How It Is Used in SSing

Jar Analyzer is intended to be used as **one part of an SSer's investigation workflow**.

A typical workflow:

```text
Player enters SS
       │
       ▼
SSer collects relevant files
       │
       ▼
Jar Analyzer scans JARs
       │
       ├── Clean
       ├── Notable
       ├── Suspicious
       ├── Detected
       └── Critical
       │
       ▼
SSer investigates the findings
       │
       ▼
Final decision based on the complete SS
```

The tool **does not automatically determine whether a player is cheating**. Findings should be reviewed by the SSer together with the rest of the SS evidence.

---

## Usage

### 1. Download

Download the latest version from **[Releases](../../releases)**.

### 2. Launch

Run:

```text
JarAnalyzer-*.exe
```

Accept the UAC prompt if requested.

### 3. Scan

Click:

```text
SCAN ALL DRIVES
```

or drag and drop a JAR file directly into the application.

---

## Detection Categories

| Category    | Examples                                  |
| :---------- | :---------------------------------------- |
| Combat      | Combat-related cheat indicators           |
| Movement    | Movement modification indicators          |
| Render      | Render manipulation indicators            |
| Bypass      | Anti-detection indicators                 |
| Injection   | Agent/injection indicators                |
| Obfuscation | Obfuscator and encrypted-code indicators  |
| Frameworks  | Known cheat/client frameworks             |
| Mixins      | Suspicious mixins                         |
| Behavioral  | Decryptors, self-destruct, shell patterns |

---

## System Requirements

| Requirement   | Supported    |
| :------------ | :----------- |
| Windows       | 10 / 11      |
| Architecture  | x64          |
| Java          | Not required |
| .NET          | Not required |
| Administrator | Recommended  |

---

## Disclaimer

Jar Analyzer is intended for **Minecraft server protection, SSing, security research, and educational purposes**.

Detection is **heuristic and signature-based** and may produce false positives or false negatives.

**Never take action against a player based solely on one Jar Analyzer result. Always review the findings and the rest of the SS evidence.**

---

## License

**Proprietary Software — All Rights Reserved**

Copyright © 2026 **ValyaR**

You may not:

* Redistribute the software
* Publish modified versions
* Remove or replace the author's name
* Claim the software as your own
* Repackage or sell the software without permission

See [`LICENSE`](LICENSE) for the full license.

---

## Credits

**Developer:** ValyaR
**Discord:** `_iaec`

**Decompiler:** CFR

---

<p align="center">
  <b>Jar Analyzer</b>
  <br>
  Minecraft SSing • JAR Analysis • Cheat Detection
</p>
