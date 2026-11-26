# Study on Singapore CSA and the EU CRA 

OpenChain Southeast Asia Work Group · 26 November 2026

## Purpose and scope

This draft presents a personal, preliminary comparison of Singapore’s cybersecurity laws and guidance with the EU Cyber Resilience Act, using the OpenChain CRA Checklist as a framework.

It is a work in progress, provided for reference and discussion only, and does not constitute legal advice.

- [OpenChain CRA Checklist](https://cra-compliance.openchainproject.org)

## Contents

- [Purpose and scope](#purpose-and-scope)
- [Singapore laws and guidance](#singapore-laws-and-guidance)
- [Checklist mapping overview](#checklist-mapping-overview)
- [Comparison by checklist section](#comparison-by-checklist-section)
- [Discussion questions](#discussion-questions)
- [External references](#external-references)

## Singapore laws and guidance

### Primary legislation

- [Cybersecurity Act 2018 and Cybersecurity (Amendment) Act 2024](https://sso.agc.gov.sg/Act/CA2018?WholeDoc=1) 
  - Main provisions commenced on 31 Aug 2018.
  - [Amendments strengthening CII protection and introducing oversight of Systems of Temporary Cybersecurity Concern (STCCs)](https://www.csa.gov.sg/news-events/press-releases/provisions-in-the-cybersecurity--amendment--act-to-come-into-force-on-31-october-2025/) commenced on 31 Oct 2025.
  - [Provisions for Entities of Special Cybersecurity Interest (ESCIs)](https://www.csa.gov.sg/news-events/events/entities-of-special-cybersecurity-interest/) commenced on 30 Oct 2026.
- [Digital Infrastructure Act 2026 (DIA)](https://assets.egazette.gov.sg/2026/Legislative%20Supplements/Acts%20Supplement/26acts27.pdf) 
  - First published in the Government Gazette on 10 Nov 2026.
  - Commencement unconfirmed.
- [Financial Services and Markets Act 2022 (FSMA), section 29](https://sso.agc.gov.sg/Act/FSMA2022?ProvIds=pr29-)
  - Part 5 (Technology Risk Management), comprising section 29, commenced on 10 May 2024.
- [Personal Data Protection Act 2012 (PDPA)](https://sso.agc.gov.sg/Act/PDPA2012?WholeDoc=1)
  - The main data protection provisions commenced on 2 Jul 2014.
- [Electronic Transactions Act 2010 (ETA)](https://sso.agc.gov.sg/Act/ETA2010)
  - Commenced **1 Jul 2010**.
- [Computer Misuse Act 1993 (CMA)](https://sso.agc.gov.sg/Act/CMA1993)
  - Commenced **30 Aug 1993**.
- [Online Criminal Harms Act 2023 (OCHA)](https://sso.agc.gov.sg/Acts-Supp/24-2023/Published/20230807?DocDate=20230807)
  - Commenced in stages on **1 Feb 2024** and **24 Jun 2024**.

### CSA code, advisory

- [Cybersecurity Code of Practice for Critical Information Infrastructure 2026 (CCoP)](https://www.csa.gov.sg/legislation/codes-of-practice/)  Issued **29 Jul 2026**.
- [Advisory on Securing the Software Supply Chain and Development Workflows (AD-2026-003)](https://www.csa.gov.sg/alerts-and-advisories/advisories/ad-2026-003/) · CSA advisory. Published **7 Apr 2026**.
- [Cybersecurity Labelling Scheme for IoT (CLS(IoT))](https://www.csa.gov.sg/our-programmes/certification-and-labelling-schemes/cybersecurity-labelling-scheme/registration/) · Product labelling scheme. Residential router Level 1 requirement effective **2 May 2022**.

### MAS notices and guidelines

**Binding notices**

- **Notice on Technology Risk Management (TRMN) and Notice on Cyber Hygiene (CHN)** · Binding MAS requirements continue through the FSM-series notices issued under FSMA §29(1), which replaced the earlier notices from **10 May 2024**. [MAS old-to-new notice reference table](https://www.mas.gov.sg/regulation/cyber-security#regulations-and-guidance)
  - **Banks** · TRMN 644 → FSM-N05. CHN 655 → FSM-N06.
- [Notices on Management of Outsourced Relevant Services (MAS Notices 658 and 1121)](https://www.mas.gov.sg/regulation/third-party-risk-management) · Binding MAS notices for banks and merchant banks. Effective **11 Dec 2024**.

**Supervisory guidance**

- [Guidelines on Risk Management Practices – Technology Risk (TRM Guidelines, TRMG)](https://www.mas.gov.sg/regulation/guidelines/technology-risk-management-guidelines) · MAS supervisory guidance. **18 Jan 2021** edition, still listed by MAS. Covers technology governance, secure development, third-party risk and open source software use.

## Checklist mapping overview

| Checklist section | Items | Singapore references |  |
| --- | ---: | --- | --- |
| 2 · Governance |  | CCoP; MAS TRM |  |
| **3 · Components & SBOM** |  | CSA advisory; MAS TRM |  |
| **4 · Vulnerability handling** |  | Cybersecurity Act; MAS notices |  |
| **5 · OSS stewardship** |  | MAS TRM; CSA advisory |  |
| 6 · Updates & support |  | CCoP; Cyber Hygiene; CLS |  |
| 7 · Technical file & sharing |  | CLS; regulatory records |  |
| 8 · Cross-framework integration |  | PDPA; MAS; AI guidance |  |
| 9 · Procurement |  | MAS outsourcing; CSA advisory |  |

## Comparison by checklist section

### Section 1: Introduction & Scope

- **OpenChain Checklist** [Section 1](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-1-introduction--scope)
- **Singapore** · [CSA Cybersecurity Act overview](https://www.csa.gov.sg/legislation/cybersecurity-act/)
  - The CII sectors are: Energy, Water, Banking and Finance, Healthcare, Transport (which includes Land, Maritime, and Aviation), Infocomm, Media, Security and Emergency Services, and Government.
  - For major cloud services and data centre facilities: [Digital Infrastructure Act 2026](https://assets.egazette.gov.sg/2026/Legislative%20Supplements/Acts%20Supplement/26acts27.pdf)
- **EU CRA** · Start with the products with digital elements (PDEs) placed on the EU market. [CRA Articles 2–3](https://publications.europa.eu/resource/cellar/21b7d4eb-a6e2-11ef-85f0-01aa75ed71a1.0006.01/DOC_1)

### Section 2: Program Architecture & Governance

- **OpenChain Checklist** [Section 2](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-2-program-architecture--governance)
- **Singapore**
  - The CCoP provides a reference for CII governance and risk management. [CSA Codes of Practice](https://www.csa.gov.sg/legislation/codes-of-practice/)
  - MAS TRM provides financial-sector guidance on technology risk governance. [MAS TRM Guidelines](https://www.mas.gov.sg/regulation/guidelines/technology-risk-management-guidelines)
- **EU CRA** · Manufacturers assess product cybersecurity risks. Product category helps determine the applicable conformity procedure. [CRA Articles 7–8, 13 and 32](https://publications.europa.eu/resource/cellar/21b7d4eb-a6e2-11ef-85f0-01aa75ed71a1.0006.01/DOC_1)

### Section 3: Component Management & SBOM Quality

**Focus 1 · What is in this product release, and can we trust its origin?**

| Checklist area | Practical work | Evidence to reuse |
| --- | --- | --- |
| 3.1–3.2 · Identification & quality | Link components and dependencies to a release | SBOM; versions, identifiers, licence and source records |
| 3.3–3.4 · Provenance & development | Verify source integrity and test the product | Hashes / signatures; build provenance; security test results |
| 3.5–3.6 · Supply-chain roles | Identify operator responsibilities; qualify suppliers | Role assessment; supplier review; component acceptance record |

- **Singapore** · [CSA AD-2026-003](https://www.csa.gov.sg/alerts-and-advisories/advisories/ad-2026-003/) recommends supply-chain controls; [MAS TRM §§6.1.3–6.1.4](https://www.mas.gov.sg/-/media/mas/regulations-and-financial-stability/regulatory-and-supervisory-framework/risk-management/trm-guidelines-18-january-2021.pdf#page=19)
  - 6.1.3 A policy and procedure on the use of third party and open-source software codes should be established to ensure these codes are subject to review and testing before they are integrated into the FI’s software.
  - 6.1.4 To facilitate the remediation of vulnerabilities in a timely manner, the FI should keep track of updates and reported vulnerabilities for third party and open-source software codes that are incorporated in the FI’s software.
- **CRA distinction** · From **11 Dec 2027**, Annex I, Part II(1): identify and document vulnerabilities and components contained in products with digital elements, including by drawing up a software bill of materials in a commonly used and machine-readable format covering at the very least the top-level dependencies of the products. [CRA legal text](https://publications.europa.eu/resource/cellar/21b7d4eb-a6e2-11ef-85f0-01aa75ed71a1.0006.01/DOC_1)

### Section 4: Vulnerability Handling & Vulnerability Exchange

| Checklist area | Decision / evidence |
| --- | --- |
| 4.1 · Monitor | Match vulnerability reports to the release SBOM |
| 4.2–4.3 · Assess & respond | Record affected status, reasoning, owner and remediation; communicate via VEX where useful |
| 4.4–4.5 · Disclose & report | Record awareness time; assess each legal trigger; assign recipient, deadline and accountable party |

- **Singapore** · The specified additional CII incidents carry a **2-hour** reporting deadline from awareness.
  - [CSA announcement](https://www.csa.gov.sg/news-events/press-releases/provisions-in-the-cybersecurity--amendment--act-to-come-into-force-on-31-october-2025/)
  - [MAS notices](https://www.mas.gov.sg/regulation/cyber-security) by indcustry.
    - A Bank must notify the Authority as soon as possible, but not later than 1 hour, upon the discovery of a relevant incident. [FSM-N05](https://www.mas.gov.sg/-/media/mas-media-library/regulation/notices/trpd/notice-fsm-n05/mas-notice-fsm-n05.pdf) “relevant incident” means a system malfunction or IT security incident, which has a severe and widespread impact on the bank’s operations or materially impacts the Bank’s service to its customers;
- **CRA manufacturer reporting**
  - Since **11 Sep 2026**: actively exploited vulnerabilities / severe product security incidents → **24h early warning; 72h notification**, from awareness and without undue delay. Final report: vulnerability **within 14 days of a corrective or mitigating measure becoming available**; incident **within one month of the incident notification**. [Articles 14 & 16](https://digital-strategy.ec.europa.eu/en/policies/cra-reporting)

### Section 5: Open Source Software (OSS) Stewardship

- **OpenChain Checklist** [Section 5](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-5-open-source-software-oss-stewardship)
- **Singapore** - *Work in progress*
  - [CSA AD-2026-003](https://www.csa.gov.sg/alerts-and-advisories/advisories/ad-2026-003/)
  - MAS guidance addresses review, testing and tracking of open-source code used by financial institutions. [MAS TRM §§6.1.3–6.1.4](https://www.mas.gov.sg/-/media/mas/regulations-and-financial-stability/regulatory-and-supervisory-framework/risk-management/trm-guidelines-18-january-2021.pdf#page=19)
- **EU CRA**
  - [Commission guidance on open source](https://digital-strategy.ec.europa.eu/en/policies/cra-open-source) Open-source software stewards are subject to the obligations laid down in Article 24, notably putting in place a cybersecurity policy to foster secure development and handling of vulnerabilities; cooperating with market surveillance authorities; reporting actively exploited vulnerabilities and severe incidents having an impact on the security of products with digital elements. In accordance with Article 64(10), open-source software stewards are not subject to administrative fines for infringements of the CRA.
  - [Reporting application dates](https://digital-strategy.ec.europa.eu/en/policies/cra-reporting) In accordance with Article 71(2) of the CRA, open-source software stewards are subject to reporting obligations (Article 24(3)) from 11 December 2027.

### Section 6: Security Updates & Support Period

- **OpenChain Checklist** [Section 6](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-6-security-updates--support-period)
- **Singapore** · MAS Cyber Hygiene covers patching for applicable institutions. [MAS Cyber Security](https://www.mas.gov.sg/regulation/cyber-security)
  - Residential router requirements include keeping software updated. [CSA residential router requirements](https://www.csa.gov.sg/news-events/press-releases/government-to-raise-cybersecurity-labelling-requirements-for-residential-routers/)
- **EU CRA** · Article 13(8) generally requires a support period of at least five years, with a shorter period where expected product use is shorter. [CRA Article 13 and Annex I](https://publications.europa.eu/resource/cellar/21b7d4eb-a6e2-11ef-85f0-01aa75ed71a1.0006.01/DOC_1)

### Section 7: Technical File & Supply Chain Sharing

- **OpenChain Checklist** · [Section 7](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-7-technical-file--supply-chain-sharing)

Work in progress.

### Section 8: Cross-Framework Integration

- **OpenChain Checklist** [Section 8](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-8-cross-framework-integration)

Work in progress

### Section 9: Procurement & Buyer-Side Obligations

- **OpenChain Checklist** [Section 9](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md#section-9-procurement--buyer-side-obligations)

Work in progress

## Follow-up learning

- The reviewed materials address selected infrastructure, sector and product requirements; the CRA establishes EU product cybersecurity requirements.
- Further map SBOM, support periods, vulnerability reporting and OSS stewardship in specific industry.
- Refine each section with sources and OpenChain links.
- Discuss key findings and gaps with Singapore stakeholders.

## Discussion questions

- TODO

## External references

Official sources used in this study are listed below. Repeated links to sections of the same document are consolidated. Agency explanations and guidance do not replace legislation.

### OpenChain checklist and standards

1. [OpenChain CRA Checklist — pinned revision, 29 October 2026, commit 11eb3ed](https://github.com/OpenChain-Project/CRA-Compliance/blob/11eb3edcb164a897e4d70ed6e58da8b938f8a299/CRA_Checklist_Requirement_latest.md)
2. [ISO/IEC 5230 — OpenChain License Compliance](https://openchainproject.org/license-compliance)
3. [ISO/IEC 18974 — OpenChain Security Assurance](https://openchainproject.org/security-assurance)

### Singapore legislation

1. [Cybersecurity Act 2018 — Singapore Statutes Online](https://sso.agc.gov.sg/Act/CA2018?WholeDoc=1)
2. [Digital Infrastructure Act 2026 — official Gazette PDF](https://assets.egazette.gov.sg/2026/Legislative%20Supplements/Acts%20Supplement/26acts27.pdf). Official context: [MDDI closing speech for the Bill's second reading, 7 October 2026](https://www.mddi.gov.sg/newsroom/closing-speech-by-sms-tan-kiat-how-for-the-second-reading-of-the-digital-infrastructure-bill/).
3. [Financial Services and Markets Act 2022, section 29](https://sso.agc.gov.sg/Act/FSMA2022?ProvIds=pr29-)
4. [Personal Data Protection Act 2012](https://sso.agc.gov.sg/Act/PDPA2012?WholeDoc=1)
5. [Electronic Transactions Act 2010](https://sso.agc.gov.sg/Act/ETA2010)
6. [Computer Misuse Act 1993](https://sso.agc.gov.sg/Act/CMA1993)
7. [Online Criminal Harms Act 2023 — official published Act](https://sso.agc.gov.sg/Acts-Supp/24-2023/Published/20230807?DocDate=20230807)

**Access note:** SSO restricts automated retrieval and may require browser verification. The DIA Gazette PDF could not be retrieved during this review; the MDDI explanation above provides an accessible official entry point. Confirm the enacted text and commencement separately.

### Cyber Security Agency of Singapore

1. [Cybersecurity Act — official overview](https://www.csa.gov.sg/legislation/cybersecurity-act/)
2. [2024 amendment provisions commencing on 31 October 2025](https://www.csa.gov.sg/news-events/press-releases/provisions-in-the-cybersecurity--amendment--act-to-come-into-force-on-31-october-2025/)
3. [Codes of Practice — official entry point for CCoP 2026](https://www.csa.gov.sg/legislation/codes-of-practice/)
4. [Securing the Software Supply Chain and Development Workflows — AD-2026-003](https://www.csa.gov.sg/alerts-and-advisories/advisories/ad-2026-003/)
5. [CLS(IoT) registration and residential router requirements](https://www.csa.gov.sg/our-programmes/certification-and-labelling-schemes/cybersecurity-labelling-scheme/registration/)
6. [Higher cybersecurity labelling requirements for residential routers](https://www.csa.gov.sg/news-events/press-releases/government-to-raise-cybersecurity-labelling-requirements-for-residential-routers/)
7. [Guidelines and Companion Guide on Securing AI Systems](https://www.csa.gov.sg/resources/publications/guidelines-and-companion-guide-on-securing-ai-systems/)

### Monetary Authority of Singapore

1. [Cyber Security — TRM and Cyber Hygiene notices and old-to-new reference table](https://www.mas.gov.sg/regulation/cyber-security#regulations-and-guidance)
2. [Third-Party Risk Management — Notices 658 and 1121 and outsourcing guidance](https://www.mas.gov.sg/regulation/third-party-risk-management)
3. [Guidelines on Risk Management Practices — Technology Risk](https://www.mas.gov.sg/regulation/guidelines/technology-risk-management-guidelines)
4. [Technology Risk Management Guidelines — 18 January 2021 PDF](https://www.mas.gov.sg/-/media/mas/regulations-and-financial-stability/regulatory-and-supervisory-framework/risk-management/trm-guidelines-18-january-2021.pdf). See sections 6.1.3–6.1.4 for third-party and OSS code.
5. [Achieving Operational Resilience for Financial Institutions in Singapore](https://www.mas.gov.sg/regulation/operational-resilience)

### EU Cyber Resilience Act

1. [Regulation (EU) 2024/2847 — official English legal text, EU Publications Office PDF](https://publications.europa.eu/resource/cellar/21b7d4eb-a6e2-11ef-85f0-01aa75ed71a1.0006.01/DOC_1)
2. [European Commission — CRA overview](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
3. [European Commission — summary of the legislative text](https://digital-strategy.ec.europa.eu/en/policies/cra-summary)
4. [European Commission — reporting obligations](https://digital-strategy.ec.europa.eu/en/policies/cra-reporting)
5. [European Commission — open source](https://digital-strategy.ec.europa.eu/en/policies/cra-open-source)

### Other EU frameworks mentioned in Section 8

These official overview pages provide navigation to the relevant instruments. Assess each framework's scope separately.

1. [European Commission — NIS2 Directive](https://digital-strategy.ec.europa.eu/en/policies/nis2-directive)
2. [European Commission — AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
3. [European Commission — financial-sector cyber resilience and DORA](https://finance.ec.europa.eu/digital-finance/cyber-resilience_en)
4. [European Commission — Data Act](https://digital-strategy.ec.europa.eu/en/policies/data-act)
5. [European Commission — eIDAS Regulation](https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation)
