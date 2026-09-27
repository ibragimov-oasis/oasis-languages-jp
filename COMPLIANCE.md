# Regulatory Compliance, Due Diligence & M&A Audit Dossier

**Project Name:** oasis-languages-jp  
**Classification:** Enterprise-Ready Proprietary Web Application  
**Auditor / Grant / Investor Reference Date:** 2026  
**Maintainer / Owner:** silent0002 / Oasis  
**Official Inquiries:** `ibragimov@akane.waseda.jp`

---

## Executive Summary for Investors, Grant Committees & M&A Evaluators
This document provides a consolidated legal, architectural, and regulatory compliance dossier for **oasis-languages-jp**. It is specifically structured to satisfy legal due diligence requirements for:
1. **Venture Capital & Angel Investment Due Diligence**
2. **Institutional & Government Grant Audits** (EU Horizon, UAE Hub71/DFF, US NSF/SBIR, University Grants)
3. **M&A Asset Acquisition & Intellectual Property Verification**

---

## 1. Intellectual Property (IP) Chain of Title & Clean Asset Verification
- **100% Proprietary Ownership:** All source code, architectural schematics, UI/UX designs, and documentation are authored and owned by the copyright holder.
- **Copyleft-Free Architecture:** The codebase is free from viral or restrictive copyleft licenses (e.g., AGPL-3.0 has been purged). It utilizes strictly commercial-safe dependencies (MIT, Apache 2.0, BSD-3) where open-source libraries are integrated.
- **Clean Assignability:** In accordance with Section 7 of our [Terms of Service](TERMS_OF_SERVICE.md), all software assets, platform contracts, and operational components are unencumbered and freely transferable to any acquiring entity, joint venture, or grant recipient organization.

---

## 2. Global Privacy & Regulatory Compliance Matrix

| Regulatory Standard | Jurisdiction | Compliance Status | Key Measures Implemented |
|---|---|---|---|
| **GDPR** (Reg. EU 2016/679) | European Union & UK | **FULLY COMPLIANT** | Lawful basis established (Art. 6); Data Subject rights framework (Arts. 15-22); DPO contact; Standard Contractual Clauses (SCCs). |
| **ePrivacy Directive** (2002/58/EC) | European Union | **FULLY COMPLIANT** | Zero third-party tracking; strictly necessary cookies and local storage only. |
| **CCPA / CPRA** | California, USA | **FULLY COMPLIANT** | Zero data selling/sharing policy; California consumer rights notice; no-discrimination guarantee. |
| **UAE PDPL** (Law No. 45/2021) | UAE, Dubai, DIFC, ADGM | **FULLY COMPLIANT** | Fair processing principles; localized rights management; cross-border safeguards. |
| **APPI** | Japan | **FULLY COMPLIANT** | Specified purpose of use; third-party transfer restrictions; administrative controls. |
| **152-FZ** | CIS / Regional | **FULLY COMPLIANT** | Consent frameworks; purpose limitation; secure client-side storage. |

---

## 3. Anti-AI Scraping & Technical Protection Framework
- **EU DSM Directive Art. 4(3) Reservation:** Machine-readable opt-out for Text and Data Mining (TDM) is technically implemented via `robots.txt` and verified in public web endpoints.
- **Bot Mitigation:** Prohibits crawling, scraping, and ingestion by 35+ major AI and data-broker user-agents (OpenAI, Anthropic, Google-Extended, ByteDance, Perplexity, Cohere, Meta, etc.).
- **Reverse Engineering Defense:** Legally binding prohibitions against decompilation and AI-assisted source cloning in the Terms of Service.

---

## 4. Technical Security & Infrastructure Safeguards
- **Encryption:** All communications enforced via HTTPS with TLS 1.3 encryption.
- **Vulnerability Protocol:** Defined in [SECURITY.md](SECURITY.md) with a private responsible disclosure channel (`ibragimov@akane.waseda.jp`).
- **Data Minimization:** No unnecessary personal data is stored on remote servers; user preferences are maintained client-side in browser storage.

---

## 5. Certification of Compliance
The software system and documentation for **oasis-languages-jp** are certified to be in full compliance with applicable international standards as of the effective date.
