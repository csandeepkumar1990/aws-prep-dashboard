# AWS Cert Prep Dashboard

## Project Overview
Single-file HTML dashboard (`index.html`) for tracking Sandeep Chandupatla's AWS certification prep journey.

## Architecture
- **Single file**: `index.html` — all CSS, JS, and HTML inline. No build tools, no dependencies except Chart.js CDN.
- **Persistence**: `localStorage` under key `aws-dash-state` — checkbox states survive page refresh.
- **Charts**: Chart.js 4.4.0 via CDN.

## Certifications Tracked (14 total)

### Foundational
- CLF-C02 — AWS Certified Cloud Practitioner
- AIF-C01 — AWS Certified AI Practitioner

### Associate
- SAA-C03 — Solutions Architect – Associate
- DVA-C02 — Developer – Associate
- SOA-C02 — SysOps Administrator – Associate
- DEA-C01 — Data Engineer – Associate
- **MLA-C01 — Machine Learning Engineer – Associate ← ACTIVE**

### Professional
- SAP-C02 — Solutions Architect – Professional
- DOP-C02 — DevOps Engineer – Professional

### Specialty
- ANS-C01 — Advanced Networking – Specialty
- SCS-C02 — Security – Specialty
- MLS-C01 — Machine Learning – Specialty
- DBS-C01 — Database – Specialty
- PAS-C01 — SAP on AWS – Specialty

## MLA-C01 Tracking Data (from Sandeep's study sheets)

### AWS Exam Prep Plan (17 items, 16h 35m)
- Step 1: Get to Know the Exam (items 1–3)
- Step 2: Refresh Knowledge — Pretest (item 4)
- Step 3: Domain Reviews + Practice + SimuLearn (items 5–15)
  - Domain 1: Data Preparation for ML
  - Domain 2: ML Model Development
  - Domain 3: Deployment & Orchestration
  - Domain 4: Monitoring, Maintenance & Security
- Step 4: Exam Readiness — Practice Exam + Summary (items 16–17)

### Udemy — Stephane Maarek Course (14 sections, 310 lectures, ~23.5h)

### Practice Tests — Pass Target ≥72%
| Instructor       | Tests | Best Score |
|-----------------|-------|------------|
| Stephane Maarek | 3     | 70%        |
| Nikolai Schuler | 4     | 87%        |
| Marlon Anesi    | 6     | 92%        |

## Design Decisions
- Dark theme with AWS orange (#FF9900) accent
- Sidebar navigation per cert, main content area
- Tabs within MLA-C01: AWS Exam Prep / Udemy Course / Practice Tests
- Non-MLA certs show a placeholder (not started) screen
- All progress auto-calculates from checkbox state
