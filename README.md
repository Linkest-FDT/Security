# Linkest Foundation Security Center

[![Security Policy](https://img.shields.io/badge/Security-Policy-critical?style=flat-square&color=red)](#)
[![CVE Numbering Authority](https://img.shields.io/badge/CNA-Coverage-blue?style=flat-square)](#)
[![GHSA](https://img.shields.io/badge/Report%20via-GHSA-success?style=flat-square)](#)

> [!WARNING]  
> **Do NOT report security vulnerabilities via public GitHub Issues.**  
> Publicly disclosing an unpatched vulnerability puts the entire open-source ecosystem at risk. Please follow the private reporting channels outlined below.

Welcome to the centralized security repository for the **Linkest Foundation** and its affiliated projects. This repository serves as the primary entry point for security researchers, white-hat hackers, and developers to report vulnerabilities, review our Vulnerability Disclosure Policy (VDP), and understand our CNA (CVE Numbering Authority) jurisdiction.

## 🚨 Reporting a Vulnerability

If you believe you have discovered a security vulnerability in any repository under the `Linkest-FDT` organization, or in one of our officially Affiliated Projects, please report it immediately through one of the following channels:

### 1. GitHub Security Advisories (Preferred)
Submit a private vulnerability report (GHSA) directly in this repository:
👉 **[Submit a GHSA Report](https://github.com/Linkest-FDT/Security/security/advisories/new)**

### 2. Email
If you cannot use GitHub, you can securely contact our security team at:
✉️ **security@linkest.org**

## 🛡️ Scope & CNA Jurisdiction

As a CVE Numbering Authority (CNA), Linkest Foundation strictly adheres to NIST and MITRE requirements. 

We **only** process vulnerability reports for:
- All official repositories under the `Linkest-FDT` organization.
- Official infrastructure and websites (`*.linkest.org`).
- **Affiliated Projects** (see criteria below).

We **cannot** process reports for unrelated third-party projects. If the vulnerability belongs to another project, please report it to their respective maintainers or CNA.

### What defines an "Affiliated Project"?
A project outside the `Linkest-FDT` organization may be eligible for our CNA coverage if it meets **BOTH** criteria:
1. The project's official `README.md` explicitly states its affiliation with Linkest Foundation.
2. The project is officially listed on the **[Linkest Foundation Website](https://linkest.org/)** under the "Projects" page.

*(Note: Affiliated Projects retain full IP ownership. Linkest only provides CVE coverage and triage support.)*

## 🤝 Safe Harbor & Rules of Engagement

We deeply value the work of the security community and commit to the following Safe Harbor principles:

- **No Legal Action:** If you act in good faith and strictly follow our VDP, we will not initiate legal action against you.
- **Public Acknowledgment:** We will happily credit you for your discovery in the security advisory and release notes (unless you prefer to remain anonymous).
- **Responsible Testing:** Do not intentionally degrade our systems. Large-scale DDoS, brute-forcing, or testing on production environments is strictly prohibited. Proof of Concepts (PoCs) must be minimal and controlled.
- **Data Privacy:** Do not access, modify, or exfiltrate real user data. Test data must be deleted immediately.

## ⏱️ Triage SLA & Disclosure Timeline

- **Initial Response:** We aim to acknowledge your report within **7 to 14 days**.
- **Triage:** We will evaluate the severity using CVSS v3.1/v4.0 and work on a patch.
- **Disclosure:** We enforce a strict **90-day responsible disclosure** policy. Once a patch is released (or the 90-day window expires), we will publish a public advisory (CVE/GHSA) detailing the vulnerability.

## 📚 Resources

- [Full Security & Disclosure Policy](https://linkest.org/security)
- [Linkest Foundation Official Website](https://linkest.org/)
- [MITRE CNA Guidelines](https://www.mitre.org/)

---
<p align="center">
  <b>CrCLARE Studio Security Team</b><br>
  <i>Protecting the open-source ecosystem with Zero Trust.</i>
</p>
