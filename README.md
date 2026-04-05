# 📧 OEmailHarvest

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20OSINT-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-requests%20beautifulsoup4-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v3.0-cyan?style=flat-square"/>
</p>

> **OEmailHarvest** is an OSINT tool that gathers emails and subdomains for a target domain using multiple public sources: crt.sh (Certificate Transparency), HackerTarget API, homepage HTML extraction, and DNSDumpster passive DNS.

**Fast, threaded, and clean results with multiple export formats.**

---

## 📌 Overview

OEmailHarvest combines several passive OSINT techniques to discover email addresses and subdomains associated with a target domain. It runs selected sources in parallel and presents results with clear statistics.

Perfect for initial reconnaissance and expanding the attack surface.

---

## 🖥️ Modules

| # | Module          | Description |
|---|-----------------|-------------|
| **[1]** | **Harvest**     | Main email & subdomain collection from selected sources |
| **[2]** | **How to Use**  | Help and detailed source information |

---

## 📊 Key Features

- **Multiple OSINT Sources**:
  - crt.sh (Certificate Transparency logs)
  - HackerTarget API (subdomain lookup)
  - Homepage HTML extraction (regex)
  - DNSDumpster (passive DNS scraping)
- **Parallel Execution** — Threaded harvesting for speed
- **Smart Parsing** — Extracts both emails and subdomains
- **Clean Results Display** — Colored output with counts
- **Multiple Export Formats** — TXT, JSON, CSV
- **Interactive Menu** — Easy source selection and configuration

---

## ⚙️ Requirements

- **requests**
- **beautifulsoup4**
  ```bash
  pip install requests beautifulsoup4
  chmod +x OEmailHarvest
  ./OEmailHarvest

  📁 Output

Live Terminal — Progress from each source with new emails/subdomains count
Results Section — Separated lists of emails and subdomains with statistics
Export Files:
.txt — Human-readable report
.json — Structured data with stats
.csv — Type + value format (email/subdomain)



📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED SECURITY TESTING / OSINT USE ONLY
