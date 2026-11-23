# 🦉 OEmailHarvest

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OEmailHarvest** — Email & Subdomain OSINT

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OEmailHarvest gathers emails and subdomains through OSINT sources such as certificate transparency and public passive DNS datasets. It can enrich resolutions, optionally brute-force DNS names, audit MX/SPF/DMARC/DKIM posture, and export multi-format reports for domains under authorised assessment.

---

## ✨ Features

- Multi-source OSINT collection (CT logs and public recon APIs)
- Subdomain enrichment with optional DNS brute-force wordlists
- Email security audit covering MX, SPF, DMARC, and DKIM signals
- WHOIS display and guess/pattern helpers for naming conventions
- TXT/JSON/CSV/HTML exports and --all for full packs
- Sandbox and TLS-verify controls for constrained environments

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OEmailHarvest example.com --audit --json
./OEmailHarvest example.com --sources A --enrich --txt
./OEmailHarvest example.com --brute --wordlist dns.txt --all
./OEmailHarvest --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*
