# 🌍 MEIL Group ESG Command Center
### Enterprise Sustainability, BRSR Reporting & Intelligence Platform

[![SEBI BRSR Core](https://img.shields.io/badge/Compliance-SEBI%20BRSR%20Core%20v2.4-006c4a?style=for-the-badge&logo=shield)](https://www.sebi.gov.in/)
[![GHG Protocol](https://img.shields.io/badge/Standard-GHG%20Protocol%20Scopes%201%2C2%2C3-0f2347?style=for-the-badge)](https://ghgprotocol.org/)
[![Assurance](https://img.shields.io/badge/Assurance-DNV%20GL%20%7C%20ISO%2014064-5784ff?style=for-the-badge)](https://www.dnv.com/)
[![TailwindCSS](https://img.shields.io/badge/UI-TailwindCSS%203.4-38bdf8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)

A comprehensive, interactive **Single Page Application (SPA)** designed for the **MEIL Group (Megha Engineering & Infrastructures Limited)** to monitor, collect, validate, and report sustainability metrics across **250 projects** spanning **24 business entities**.

---

## 📌 Key Highlights & Modules

### 1. 📊 Executive Overview Dashboard
- **Composite Health Score**: Live ESG composite score calculated across Environmental, Social, and Governance pillars (81.4 / 100 - Tier 1 Leader).
- **Trajectory Visualizer**: Real-time reporting cycle trajectory against annual benchmarks using smooth inline vector graphics.
- **GHG Emissions Inventory**: Scope 1 (Direct), Scope 2 (Market-based Electricity), and Scope 3 (Value Chain) breakdown with YoY variances.
- **Entity Reporting Matrix**: Live status tracker across all 24 group subsidiaries (Infrastructure, Power, Water Solutions, Construction, International).
- **Urgent Action Center**: Real-time priority alerts for missing utility bills, sensor calibration lapses, and compliance blockers.

### 2. 📋 ESG Data Collection & Ingestion Hub
- **Multi-Dimensional Filter Matrix**: Filter metrics by Fiscal Year, Group Entity, Business Unit/Division, Project Site, ESG Domain, and Assurance Status.
- **Visual Asset Telemetry**: High-altitude sites (Zojila Tunnel), hydro infrastructure (Polavaram Right Canal), and renewable power clusters (Pavagada Solar Park).
- **Consolidated Site Metrics Log**: Granular log with metric indicators, unit measurements, assigned officers, and attached audit evidence.
- **Interactive Metric Entry Modal**: Standardized slide-over drawer to log new ESG indicators with automated AI anomaly checks and immutable ledger hashing.

### 3. 📑 SEBI BRSR Reporting & Disclosure Engine
- **Three-Tier Reporting Structure**:
  - **Section A**: Master Data & General Disclosures (Workforce demographics, holding/subsidiary entities, CSR coverage).
  - **Section B**: Management & Process Disclosures (Board governance, oversight policies, grievance mechanisms).
  - **Section C**: Principle-Wise Disclosures covering **NGRBC Principles 1 through 9**.
- **Principle 6 Deep Dive**: Interactive data collection for Energy Intensity (EI 6.1), Water Intensity & Rainwater Harvesting (EI 6.2), and Scope 1/2 GHG verification (EI 6.3).
- **Multi-Tier Sign-off Pipeline**: Site Field Engineer ➔ Group ESG Compliance Lead ➔ CFO & Managing Director sign-off stream.

### 4. 🛡️ Validation & Assurance Hub
- **Rule Verification Engine**: 312 rules continuously evaluated against SEBI Core Circulars and statutory thresholds with an active 97.1% pass rate.
- **Third-Party Provider Tracking**: Status workflows for accredited external auditors (**DNV GL Business Assurance** & **Ernst & Young LLP**).
- **Chronological Audit Trail**: SHA-256 encrypted live audit stream tracking timestamped entries, ledger hashes, and automated cross-validations.

---

## 🛠️ Technology Stack

- **Core**: Vanilla HTML5, Modern ECMAScript (ES6+)
- **Styling**: Tailwind CSS (with bespoke MEIL theme color palette and design tokens)
- **Icons & Typography**: Google Fonts (`Inter`, `JetBrains Mono`, `Material Symbols Outlined`)
- **Architecture**: Zero-dependency Client-Side Single Page Application (SPA)

---

## 🚀 Quick Start

### Running Locally
No build step or Node.js runtime required! Simply clone and open:

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/meil-esg-command-center.git

# 2. Navigate to project directory
cd meil-esg-command-center

# 3. Open in your default browser (Windows)
start index.html

# Or on macOS:
# open index.html

# Or on Linux:
# xdg-open index.html
```

---

## 📂 Project Structure

```
meil-esg-command-center/
├── index.html        # Unified Single Page Application (all 4 modules + navigation)
├── README.md         # Personalized project documentation
└── .gitignore        # Standard Git ignore rules
```

---

## 📜 Compliance & Regulatory References

- **SEBI BRSR Core**: Circular No. `SEBI/HO/CFD/CFD-SEC-2/P/CIR/2023/122`
- **GHG Protocol**: Corporate Accounting and Reporting Standard
- **CEA Power Sector Baseline**: Version 19.0 Grid Emission Factors
- **ISO 14064 / ISAE 3000**: Third-Party Independent Assurance Framework

---

## 👨‍💻 Author & Maintainer

Developed for **MEIL Group Sustainability & Corporate Governance Directorate**.  
*Lead Compliance Executive: Dr. Sunita Rao, Chief ESG Officer.*
