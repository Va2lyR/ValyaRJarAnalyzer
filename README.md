# Jar Analyzer — Minecraft Cheat Detector

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-8B0000?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Architecture-x64-8B0000?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/Status-Stable-8B0000?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <b>Advanced JAR analysis and Minecraft cheat detection tool.</b><br>
  Developed by <b>ValyaR</b>
</p>

<p align="center">
  Discord: <code>_iaec</code>
</p>

---

## Overview

**Jar Analyzer** is a Windows-based tool designed to analyze Minecraft JAR files and identify cheats, ghost clients, suspicious components, obfuscation indicators, and other potentially malicious or unauthorized modifications.

The analyzer performs deep inspection of JAR archives and their classes using signature-based detection, weighted scoring, and behavioral analysis.

> **Built for Minecraft server protection, Screen Sharing (SS), and security analysis.**

---

## Features

### 🔍 Deep JAR Analysis

* Constant-pool analysis
* Class-level inspection
* Nested JAR detection
* Manifest analysis
* Archive structure analysis
* Suspicious file detection
* Large-scale JAR scanning

### 🧬 Cheat Detection

Detects indicators associated with:

* Combat modules
* Movement modules
* Render modules
* Bypass modules
* Ghost clients
* Cheat frameworks
* Suspicious mixins
* Known cheat families
* Obfuscation markers

Known families and frameworks may include:

* Dqrkis
* Doomsday
* Nova
* Vape
* Meteor
* And many others

### ⚖️ Weighted Detection System

Every detection signature is assigned a weight from **1–4**.

Multiple findings are combined to produce a final verdict instead of relying on a single signature.

| Verdict           | Description                       |
| ----------------- | --------------------------------- |
| 🟢 **Clean**      | No significant indicators found   |
| 🔵 **Notable**    | Weak or low-confidence indicators |
| 🟡 **Suspicious** | Requires further investigation    |
| 🟠 **Detected**   | Strong cheat-related indicators   |
| 🔴 **Critical**   | Strong cheat or family match      |
| ⚫ **Unreadable**  | Archive could not be analyzed     |

### 🕵️ Behavioral Analysis

Jar Analyzer can identify suspicious combinations and behavioral patterns, including:

* Agent injection indicators
* String decryptors
* Self-destruct routines
* Hollow-shell patterns
* Suspicious class combinations
* Obfuscation behavior

### 💻 Built-in Decompiler

Includes a built-in **CFR-powered decompiler** with:

* Source-code viewing
* Code search
* Multiple themes
* HTML export
* Suspicious-code investigation

### 🌍 Bilingual Interface

Available in:

* 🇺🇸 English
* 🇸🇦 العربية

With a dark red interface designed for quick analysis during SS sessions.

### 📦 Portable

* Single executable
* No Java installation required
* No .NET installation required
* Designed for Windows 10/11 x64

---

## Usage

### 1. Download

Download the latest release from:

**[Releases](../../releases)**

### 2. Launch

Run:

```text
JarAnalyzer-*.exe
```

Accept the UAC prompt when requested.

### 3. Scan

Use:

```text
SCAN ALL DRIVES
```

to scan available drives for JAR files.

You can also **drag and drop a JAR file** directly into the application.

---

## Detection Engine

Jar Analyzer combines several detection methods:

```text
JAR
 │
 ├── Archive Analysis
 │
 ├── Manifest Analysis
 │
 ├── Constant Pool Analysis
 │
 ├── Class Analysis
 │
 ├── Signature Detection
 │
 ├── Behavioral Rules
 │
 └── Weighted Scoring
          │
          ▼
       Verdict
```

This approach helps reduce reliance on a single detection signature.

---

## Detection Categories

| Category    | Examples                                           |
| ----------- | -------------------------------------------------- |
| Combat      | Reach, KillAura-related indicators, combat modules |
| Movement    | Movement modification indicators                   |
| Render      | Render manipulation indicators                     |
| Bypass      | Anti-detection and bypass indicators               |
| Injection   | Agent and injection indicators                     |
| Obfuscation | Obfuscator and encrypted-code indicators           |
| Frameworks  | Known cheat/client framework signatures            |
| Mixins      | Suspicious or cheat-related mixins                 |
| Behavioral  | Self-destruct, decryptor, shell patterns           |

---

## System Requirements

| Requirement   | Minimum         |
| ------------- | --------------- |
| OS            | Windows 10 / 11 |
| Architecture  | x64             |
| Java          | Not required    |
| .NET          | Not required    |
| Administrator | Recommended     |

---

## False Positives

No signature-based detection system can guarantee perfect results.

Legitimate mods may contain:

* Obfuscated code
* Mixins
* Injected classes
* Custom class loaders
* Encryption/decryption systems
* Libraries shared with cheat clients

**Always review the findings before taking action against a player.**

---

## Disclaimer

Jar Analyzer is provided for **educational, research, and Minecraft server-protection purposes**.

Detection is heuristic and signature-based. The results should be treated as indicators rather than absolute proof.

The developer is not responsible for actions taken solely based on the tool's detection results.

---

## License

This project is **proprietary software**.

Copyright © 2026 **ValyaR**. All rights reserved.

You may not:

* Redistribute the software
* Publish modified versions
* Remove or replace the author's name
* Claim the software as your own
* Sell or repackage the software without permission

See [`LICENSE`](LICENSE) for the complete license terms.

---

## Credits

### Developer

**ValyaR**

Discord: **`_iaec`**

### Decompiler

Powered by **CFR**.

---

<p align="center">
  <b>Jar Analyzer</b><br>
  Minecraft JAR Analysis & Cheat Detection
</p>
