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
