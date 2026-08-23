# Awesome-Third-Party-Risk-Exchange

# Top Third-Party Risk Exchange / TPRM Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Vendor Risk Management, Security Ratings, Continuous Monitoring, Questionnaires, Due Diligence & Supply-Chain Cyber Risk*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Third-Party Risk Management (TPRM)** and security rating exchanges. These tools help organizations assess, monitor, and manage cyber and operational risk introduced by vendors and suppliers through outside-in ratings, questionnaires, continuous scanning, and workflow automation.

**Examples** include SecurityScorecard, BitSight, Black Kite, Panorays, UpGuard, ProcessUnity, Whistic, OneTrust Vendorpedia, Prevalent, and RiskRecon (the category leaders).

**Open-source emphasis**: Fully featured open-source TPRM platforms are emerging. This section is expanded with the strongest available self-hosted vendor risk tools, GRC platforms with TPRM modules, security scoring projects, and related frameworks that security teams can deploy without proprietary lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[SecurityScorecard](https://securityscorecard.com/)**  
  Leading security ratings platform providing continuous outside-in scores, threat intelligence, and portfolio-level third-party risk visibility.

- **[BitSight](https://www.bitsight.com/)**  
  Cyber risk ratings platform focused on continuous monitoring of third-party and internal security posture with financial-impact insights.

- **[Black Kite](https://blackkite.com/)**  
  Third-party cyber risk platform offering detailed technical ratings, vulnerability insights, and risk quantification for vendor portfolios.

- **[Panorays](https://panorays.com/)**  
  Automated third-party security risk management platform combining external scanning with collaborative assessment workflows.

- **[UpGuard](https://www.upguard.com/)**  
  Comprehensive TPRM and attack-surface management platform with vendor ratings, continuous monitoring, questionnaires, and breach risk insights.

- **[ProcessUnity](https://www.processunity.com/)**  
  Enterprise third-party risk and GRC platform supporting vendor lifecycle management, assessments, and compliance workflows.

- **[Whistic](https://www.whistic.com/)**  
  Vendor assessment and trust exchange platform focused on security questionnaires, evidence collection, and streamlined due diligence.

- **[OneTrust Vendorpedia](https://www.onetrust.com/)**  
  Vendor risk and privacy management capabilities within the OneTrust platform, including assessment libraries and continuous monitoring integrations.

- **[Prevalent](https://www.prevalent.net/)**  
  Third-party risk management platform covering vendor onboarding, assessments, continuous monitoring, and risk reporting.

- **[RiskRecon (Mastercard)](https://www.riskrecon.com/)**  
  Cyber risk rating and continuous monitoring platform focused on actionable third-party security insights.

## Open-Source GitHub Projects
- **[Fair TPRM](https://www.fairtprm.com/)**  
  Free, open-source TPRM and GRC platform combining vendor lifecycle management, risk assessments, FAIR quantification, compliance frameworks, and continuous security monitoring in a self-hosted package.

- **[LT-VRM](https://github.com/learntprm-design/lt-vrm)**  
  Free and open-source Third-Party / Vendor Risk Management platform supporting assessments, security questionnaires, risk scoring, contract management, monitoring, and a vendor portal.

- **[RiskHub](https://github.com/W1z4rd1c4/RiskHub)**  
  Open-source risk operations platform for governed risks, controls, KRIs, vendors, approvals, and evidence management.

- **[OpenSSF Scorecard](https://github.com/ossf/scorecard)**  
  Open-source tool that automatically assesses security health metrics of open-source projects, useful for evaluating the risk of third-party dependencies and software supply chain components.

- **[CISO Assistant](https://github.com/)**  
  Open-source GRC platform with compliance framework mapping and risk assessment capabilities that can support vendor risk programs.

- **[TPRM program templates and registers](https://github.com/)**  
  Community-shared risk-based tiering models, due-diligence questionnaires, and vendor risk registers aligned to ISO 27001, DORA, NIST, and similar frameworks.

- **[Security questionnaire and evidence collection tools](https://github.com/)**  
  Open frameworks and form engines adapted for standardized vendor security questionnaires and evidence tracking.

- **[External attack-surface scanning open tools](https://github.com/)**  
  Open-source scanners and monitoring scripts that can feed basic outside-in signals into a custom TPRM process.

- **[Vendor inventory and workflow engines](https://github.com/)**  
  Self-hosted tools for maintaining vendor inventories, tiering, onboarding/offboarding checklists, and approval workflows.

- **[FAIR and quantitative risk open libraries](https://github.com/)**  
  Open implementations and helpers for Factor Analysis of Information Risk (FAIR) style quantification that can be applied to third-party scenarios.

### Additional Strong Open-Source Options
- Spreadsheet + database hybrids for smaller vendor portfolios.
- Integration of commercial rating APIs (where licensed) into open GRC platforms.
- Open policy and control libraries mapped to common frameworks (NIST CSF, ISO 27001, SOC 2).
- Notification and escalation workflows built on open automation tools (n8n, Temporal, etc.).
- Dashboards (Grafana, Metabase) for visualizing vendor risk posture and trends.

**Frameworks for building custom systems**: Deploy **Fair TPRM** or **LT-VRM** as the core vendor risk and assessment platform, enrich with **OpenSSF Scorecard** (and similar) for open-source component risk, maintain a structured vendor inventory and tiering model, and surface results in open dashboards. Add external scanning signals where available and keep all evidence and audit trails under your control. This stack provides a capable, no-license-cost foundation for TPRM, though it lacks the global continuous rating coverage and threat-intelligence depth of commercial security-rating networks.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Third-party risk management involves legal, contractual, and regulatory obligations. Open-source tools offer excellent transparency and cost control but still require proper process design, data quality, and integration with procurement, legal, and security operations. Ratings and scores are indicators, not guarantees.
- Always validate critical vendor decisions with appropriate due diligence and contractual protections.

---
**Made for security, GRC, and procurement teams building practical third-party risk programs.**
Let's make vendor risk management more accessible, transparent, and community-supported.
