# FDA Oncology Approval Landscape (2023–2026)

A competitive intelligence analysis of FDA oncology and hematologic malignancy drug approvals to understand sponsor activity, therapeutic focus areas, and emerging innovation trends.

This project uses SQL and Power BI to analyze FDA oncology approvals and identify trends across companies, cancer types, treatment modalities, and biomarker-defined therapies.

## Project Objective

The objective of this project was to analyze the FDA oncology approval landscape between 2023 and mid-2026 and answer key business questions:

* Which companies are leading oncology approval activity?
* Which cancer types attract the highest level of competition?
* What treatment modalities dominate the current landscape?
* How significant is the role of biomarker-driven therapies?
* What strategic insights can be derived from approval activity?

## Dataset Overview

The dataset was created using FDA Oncology and Hematologic Malignancy Approval Notifications and was cleaned and enriched for analysis.

**Dataset Statistics**

* Total Approvals: 158
* Companies: 59
* Cancer Types: 83
* Time Period: 2023 to mid-2026

## Tools Used

* SQL (SQLite / DB Browser)
* Power BI
* Microsoft Excel

## Repository Structure

```text
data/
├── fda_oncology_approvals.csv

sql/
├── oncology_queries.sql

dashboard/
├── FDA_Oncology_Market_Intelligence_Dashboard.pbix

docs/
├── Dashboard Screenshots
├── Competitive Intelligence Brief.pdf
```

## Dashboard Overview

### Page 1: Market Overview

Provides a high-level view of the oncology approval landscape through KPI cards, yearly approval trends, and the most active cancer indications.

### Page 2: Competitive Benchmarking

Compares sponsor activity across companies and highlights market concentration within the oncology approval landscape.

### Page 3: Approvals by Cancer Type

Analyzes approval distribution across cancer indications and compares solid versus hematologic malignancies.

### Page 4: Innovation & Company Focus

Explores treatment modalities, biomarker-defined approvals, and company focus areas through cross-sectional analysis.

## Key Findings

* NSCLC was the most active therapy area with 20 approvals, followed by Multiple Myeloma with 8 approvals.
* The market included 59 companies, but approval activity was concentrated among a small group of sponsors.
* AstraZeneca, Bristol Myers Squibb, Janssen Biotech, and Merck each recorded 12 approvals.
* The top 10 companies accounted for approximately 54% of all approvals.
* Solid tumors represented approximately 69% of approvals, while hematologic malignancies accounted for around 29%.
* ADCs recorded 17 approvals, highlighting the growing presence of newer therapeutic modalities.
* Approximately 18% of approvals were biomarker-defined, reflecting the increasing importance of precision oncology.

## Business Insights

While 59 companies received approvals during the study period, activity was concentrated among a small group of sponsors. At the same time, 34 companies recorded only one approval, highlighting the presence of many niche competitors.

NSCLC recorded the highest approval activity, suggesting a highly competitive environment where differentiation through biomarkers, modality, or clinical positioning may be important.

ADCs, cell therapies, and biomarker-defined treatments accounted for a meaningful share of approvals, reflecting the growing focus on precision oncology and next-generation therapies.

## Data Preparation

The dataset was prepared through the following steps:

* Removal of duplicate records
* Standardization of company names
* Classification of tumor categories
* Categorization of treatment modalities
* Identification of biomarker-defined therapies
* Validation of derived fields using Excel

## Limitations

* 2026 represents a partial year and should not be directly compared with prior full-year totals.
* The analysis is based on approval counts and does not include revenue, market share, sales performance, or clinical outcomes.
* The project focuses on approved therapies and does not evaluate pipeline assets or ongoing clinical trials.

## Author

Rupal Nigam

MBA (Hospital & Healthcare Management) | MSc Microbiology

Healthcare Analytics | Market Intelligence | Strategy & Consulting
