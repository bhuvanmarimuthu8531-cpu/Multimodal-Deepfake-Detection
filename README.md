# CYBERNEXUS AI
## Global Cybercrime Intelligence, Multi-Modal Deepfake Forensics, Fraud Detection & Cross-Incident Threat Correlation Platform

CYBERNEXUS AI is a production-grade cybercrime intelligence and digital forensics platform engineered for law enforcement agencies, cyber defense cells, accredited digital forensic examiners, and financial crime investigators.

---

## 1. Technical Architecture & Modules

### Frontend Architecture
- **Framework**: React 19 + TypeScript + Vite
- **Styling**: Modern White (#FFFFFF) & Light Grey (#F8FAFC) palette, Tailwind CSS v4
- **Network Graphing**: Cytoscape.js with Force-Directed (CoSE), Concentric & Hierarchical topologies
- **Data Visualizations**: Recharts Area, Bar, and Donut analytics
- **Client Document Generation**: jsPDF court-admissible forensic dossier exporter with FIPS 180-4 cryptographic seals
- **State & Access Control**: React Context RBAC with 1-click role switcher

### Backend & AI Engine
- **Server**: Express + Node.js (Full-Stack REST Architecture)
- **Database Engine**: Relational schema + Cytoscape graph topology (Cases, Evidence Hashes, Indicators, Relationships, Decisions, Audit Trail)
- **AI Models & Frameworks**:
  - `@google/genai` (SDK model `gemini-3.8-flash`) for real-time investigation assistant reasoning
  - DeepForensic MultiScale-ViT + ELA Frequency Net for multi-modal deepfake detection
  - Neural Vocoder Prosody & Phase Artifact detector for AI voice cloning
  - Lexical Entropy & Lookalike Domain clustering for phishing detection
  - Multilingual Tamil (தமிழ்) & English scam normalizer

---

## 2. Complete Module Index

| Module | Name | Primary Capabilities |
|---|---|---|
| **Module 1** | **Dashboard & Cybercrime Analytics** | Real-time database metrics, vector severity distribution, weekly trend charts, model accuracy bars |
| **Module 2** | **Multi-Modal Deepfake Forensics** | Video, Image & Audio ingestion, SHA-256 preservation, ViT spectral breakdown, frame timeline |
| **Module 3** | **AI Voice-Cloning & Impersonation** | Voice cloning detection, acoustic flatness heuristics, "Digital Arrest" & extortion lever NLP |
| **Module 4** | **Phishing & Digital Fraud Detection** | URL lexical entropy, Punycode / IDN detection, typosquatting domain clustering, IOC extraction |
| **Module 5** | **Cybercrime Relationship Graph** | Interactive Cytoscape.js canvas, node search, layout algorithms, investigator decisioning |
| **Module 6** | **Cross-Incident Intelligence Engine** | Automated nexus correlation across SHA-256 hashes, C2 IPs, and semantic scam patterns |
| **Module 7** | **Digital Forensics & Evidence Vault** | Immutable WORM storage, FIPS 180-4 SHA-256 hash validation, chain-of-custody audit logs |
| **Module 8** | **Global Threat Intelligence** | Ingestion feeds (CERT-In, INTERPOL, CISA), STIX 2.1 JSON export, IOC search |
| **Module 9** | **AI Investigation Assistant** | Gemini API integration, evidence summarization, gap analysis, multi-incident comparative reasoning |
| **Module 10**| **Multilingual Scam Analysis** | Specialized Tamil (தமிழ்) and English scam classification, dual-view original text preservation |
| **Module 11**| **Victim Reporting & Case Management** | Case intake wizard, lifecycle transitions (Submitted -> Investigation -> Resolved), officer notes |
| **Module 12**| **Risk Prioritisation, Security & Audit** | Model verification metrics (Precision/Recall/F1), tamper-evident immutable audit logs |

---

## 3. User Roles & RBAC Matrix

1. **Lead Investigator (`investigator`)**: Review cases, confirm or reject candidate correlations, add case annotations, export certified forensic PDF dossiers.
2. **Forensic Analyst (`analyst`)**: Run ViT deepfake inspections, acoustic voice cloning scans, inspect phishing targets, query Gemini investigation assistant.
3. **Super Administrator (`administrator`)**: Manage operators, assign roles, access tamper-evident audit logs, configure model sensitivity thresholds.
4. **Complainant / Citizen (`reporter`)**: Submit incident intake reports, attach evidence files, track investigation progress.

---

## 4. Quick Start & Local Execution

### Prerequisites
- Node.js 18+ or Node.js 20+
- npm or yarn

### Installation
```bash
npm install
```

### Starting the Application
```bash
npm run dev
```
The application will launch on **http://localhost:3000**.
