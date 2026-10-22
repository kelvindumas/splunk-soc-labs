# 🔎 Splunk SOC Labs

Hands-on **Splunk** labs focused on **Security / SOC**, documented step by step as I learn.

👤 **Author:** Kelvin Dumas · [GitHub](https://github.com/kelvindumas)

---

## 🎯 Goal
Learn Splunk from scratch up to real incident investigations, building a public portfolio of detections, dashboards and investigation reports.

## 🗺️ Learning Path

| # | Module | Status |
|---|--------|--------|
| 0 | [Environment setup](docs/00-setup.md) | ✅ Done |
| 1 | Fundamentals: architecture, index, sourcetype, host, source | 🟡 In progress |
| 2 | Data ingestion: upload, file monitoring, Universal Forwarder, HEC | ⚪ |
| 3 | Basic SPL: `search`, `stats`, `table`, `eval`, `where`, `rex`, `timechart` | ⚪ |
| 4 | Knowledge objects: field extractions, lookups, tags, event types, macros | ⚪ |
| 5 | Dashboards and alerts | ⚪ |
| 6 | Security labs: brute force, Sysmon, Boss of the SOC, MITRE ATT&CK | ⚪ |
| 7 | Capstone: full incident investigation | ⚪ |

## 🧪 Labs

| Lab | Topics | MITRE ATT&CK |
|-----|--------|--------------|
| [Lab 01 — First SPL search](labs/lab-01-first-spl-search/) | `index`, `sourcetype`, `stats`, `sort`, `head` | — |

## 🛠️ Environment
- Splunk Enterprise 10.6 (Free/Trial license) installed on Windows 11
- Git, VS Code

## 📁 Structure
```
labs/      → one folder per lab (README, SPL queries, screenshots)
docs/      → study notes and setup
data/      → sample data used in labs (public/synthetic only)
```

> ⚠️ All data used here is public or synthetic. No real company data.
