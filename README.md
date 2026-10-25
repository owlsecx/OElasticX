# 🦉 OElasticX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OElasticX** — Offline Elasticsearch / OpenSearch Config Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OElasticX — Offline Elasticsearch / OpenSearch Config Auditor. It provides tolerant stdlib YAML-subset parser (nested + dotted keys, flow/block lists, quoting, line origin, tabs, duplicates); Elasticsearch / OpenSearch flavour detection & aliasing. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Tolerant stdlib YAML-subset parser (nested + dotted keys, flow/block lists, quoting, line origin, tabs, duplicates)
- Elasticsearch / OpenSearch flavour detection & aliasing
- Exposure, security off, TLS, anonymous, default passwords, scripting / Groovy, CORS *, discovery, path.* permissions
- jvm.options, file realm, roles.yml, internal_users.yml
- CIS-ES control groups + CWE + MITRE ATT&CK mapping
- --root discovery, systemd units, TXT/MD/JSON/CSV/SARIF, self-test --demo, CI gates --fail-on / --min-severity

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OElasticX                                     # interactive menu
./OElasticX --scan -r /path/to/root
./OElasticX --demo
./OElasticX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
