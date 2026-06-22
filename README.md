## 📊 Data Analytics & Visual Report Workspace
### Project: Automated Visual Data Report
* **Role:** Data Analyst (Regional Development Council)
* **Target Audience:** Regional Policymakers & LGU Department Heads
#### Topic: Davao Region Local Revenue Collection Index (Mock CSV Analysis)

---

#### 1. Data Cleaning Protocol Log
* **Raw Input Problem:** The source financial CSV file contained multiple unrecorded registry fields for fiscal year 2024 alongside corrupted numerical string formats (mixing local currency 'PHP' strings directly into numerical columns).
* **AI Cleaning Instruction:** "Scan this financial dataset. Identify all null rows in the 'Tax_Revenue' column and replace them with the regional median value. Strip out all 'PHP' text formatting strings from the cells and convert the column data type to pure floating-point integers for calculation. Output the first 5 rows."
* **Result:** Successfully normalized and formatted 150 administrative row entries across five provincial clusters.

---

#### 2. Visualizations Generated

*(Embedded High-Contrast Bar Chart showing Business Tax Collection Volatility from 2021–2025)*

| Year | Business Tax (PHP M) | Event Flag |
|------|---------------------|------------|
| 2021 | 184.20 | Baseline |
| 2022 | 198.50 | Growth year |
| 2023 | 201.30 | Peak |
| 2024 | 173.10 | **Tax Amnesty Ordinance** |
| 2025 | 185.80 | Partial recovery |

*(Embedded Multi-Line Chart: Provincial Revenue Cluster Comparison — Davao del Sur vs. Davao del Norte vs. Davao de Oro, 2021–2025)*

| Year | Davao del Sur (PHP M) | Davao del Norte (PHP M) | Davao de Oro (PHP M) |
|------|-----------------------|------------------------|----------------------|
| 2021 | 72.10 | 65.40 | 46.70 |
| 2022 | 78.30 | 69.20 | 51.00 |
| 2023 | 80.50 | 71.80 | 49.00 |
| 2024 | 68.40 | 61.50 | 43.20 |
| 2025 | 74.10 | 66.30 | 45.40 |

> The provincial breakdown chart reveals that the 2024 revenue contraction was not uniform — Davao de Oro showed the steepest relative decline and the slowest recovery, suggesting that smaller, less commercially dense LGUs are disproportionately affected by tax policy transitions compared to larger provincial clusters.

---

#### 3. Human Analytical Narrative (The 'Why' Factor)

"The generated bar chart reveals a sharp 14% contraction in municipal business tax collections centered in fiscal year 2024. While the automated AI summary insight assumed this drop was caused by standard macroeconomic business closures, human cross-referencing of local policy changes reveals a different story.

This drop directly matches the grace period timeline of a newly implemented regional tax amnesty ordinance and localized business registration restructuring. This proves that LGUs need human financial analysts to properly separate structural policy transitions from actual economic downturns."

---
---

# The Davao LGU Public Health Announcement Prompt System

---

## 1. System Prompt Template (V3 – Final Optimized)

"Act as a Public Health Communications Officer working under the City Health Office of Davao del Norte. Your objective is to draft a 250-word community health announcement script for barangay-level dissemination.

**Context:** Barangay health workers in rural Davao del Norte are conducting door-to-door dengue prevention campaigns during the rainy season. Residents in sitios along the Tagum-Pantukan corridor have low health literacy and limited access to digital media.

**Constraints:** Use a warm, community-centered tone in plain Filipino-English (no medical jargon). Do NOT reference national DOH statistics or global health data — focus entirely on local barangay landmarks and community health volunteers by name role (e.g., 'your Barangay Health Worker'). Do not use clinical or bureaucratic language.

**Format:** Output in clear Markdown with exactly three sections under the headings: '### Alerto', '### Ano ang Gagawin', and '### Makipag-ugnayan'."

---

## 2. Prompt Battle Table

| Version | Prompt Modifier Added | Output Quality Reflection |
|---------|----------------------|--------------------------|
| V1 | "Write a dengue prevention announcement for Davao." | Too broad. Output was generic and referenced national DOH campaign slogans irrelevant to barangay-level audiences. Tone was formal and distant. |
| V2 | Added barangay health worker persona and rainy season context. | Better, but the language remained overly clinical and used unfamiliar medical terms like 'vector control' and 'larval surveillance' that rural residents would not understand. |
| V3 | Added Filipino-English plain language constraint, local corridor reference, three-section format, and explicit ban on national statistics. | Target hit. Output was warm, hyper-localized to Davao del Norte, and structured for easy reading aloud by barangay health workers during door-to-door visits. |

---

## 3. Visual Branding Asset

- **Engine Used:** Canva Magic Media / DALL-E 3
- **Visual Prompt:** "A flat minimalist vector logo of a barangay health worker holding a megaphone, standing in front of a rural Mindanao landscape with coconut trees and a stilted wooden house. Clean lines, no gradients. Color palette: deep green, white, and warm yellow. Style: Philippine government infographic poster."
- **Design Constraints Applied:** No photorealistic rendering. No Western suburban settings. No generic red-cross medical symbols. Grounded entirely in Mindanao rural visual identity.
- **Asset Description:** The icon is intended for use on tarpaulin health advisories and barangay bulletin boards across Davao del Norte municipalities.

---

*Submitted to: Prompt Engineering (Text & Image Generation) | Course: 99-006 GE 0000 Summer 2026*
*Role: Digital Solutions Architect — LGU Technical Working Group, Davao Region*
