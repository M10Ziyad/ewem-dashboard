# Goa E-Waste Intelligence Dashboard

An interactive, browser-based dashboard and analytical report built around a **synthetic e-waste dataset for Goa, India**. It is designed for academic projects, data analysis practice, and dashboard demonstrations.

> **Important data notice:** This project uses artificially generated data. It is not official data from the Government of Goa, CPCB, SPCB, or any real facility. Fictional facility names, IDs, compliance records, monitoring results, and locality records must not be presented as verified real-world facts.

## Project Files

- `Goa_EWaste_Dashboard_Report.html` — standalone dashboard with charts, filters, a data explorer, and an integrated report.
- `Goa_Synthetic_EWaste_Dataset_70000_Rows.xlsx` — Excel workbook containing 70,000 synthetic records across seven data sheets.

Keep the HTML and Excel files together for convenient project organisation. The dashboard is intended to run directly in a modern browser and does not require a web server or installation.

## Features

- Dashboard overview with KPI cards.
- Interactive charts for the main e-waste data domains.
- District and year filters.
- Data Explorer for browsing and searching dataset records.
- Integrated analytical report with observations, methodology, recommendations, and limitations.
- Browser print support, including the option to save the report as a PDF.
- Responsive layout for desktop and smaller screens.

## Dataset Overview

The Excel workbook contains **7 data sheets × 10,000 records = 70,000 synthetic records**, plus supporting notes and a scorecard.

| Dataset sheet | What it contains |
|---|---|
| `1_Generation_Inventory` | Synthetic e-waste generation by district/local area, equipment category, estimated population, and date |
| `2_Collection_Log` | Synthetic generated and collected quantities, collection-centre counts, and EPR targets |
| `3_Recycling_Infrastructure` | Fictional recovery-unit names and IDs, capacity, processing, and recovery-rate fields |
| `4_Compliance_Tracker` | Fictional EPR entities, compliance statuses, inspection flags, and penalty fields |
| `5_Informal_Sector_Hotspots` | Synthetic locality/cluster records, worker estimates, status, and action fields |
| `6_Env_Health_Monitoring` | Synthetic monitoring categories and result labels; not actual test or health records |
| `7_Awareness_Programs` | Synthetic outreach programs, audience groups, dates, and participation counts |

The generated data covers dates from **2020 through 2026** and includes the districts/areas represented in the workbook. Values are randomized for demonstration and should not be interpreted as measured totals, official trends, or validated geographic statistics.

## How to Run

1. Download `Goa_EWaste_Dashboard_Report.html`.
2. Open the file in a current version of Google Chrome, Microsoft Edge, or another modern browser.
3. Use the district and year filters to explore the dashboard.
4. Browse records using the Data Explorer.
5. Go to the report section to read the analysis.
6. Use the report's print option, or press `Ctrl + P` in the browser, and choose **Save as PDF** if you need a PDF copy.

No Python environment, database, Node.js setup, or local server is required to open the standalone HTML dashboard.

## Suggested Project Workflow

1. Open the dashboard and explore the charts and filters.
2. Open the Excel workbook to inspect the source tables and field names.
3. Use Python with pandas for additional exploratory data analysis, or import the workbook into Power BI for a separate report.
4. When presenting results, clearly label them as synthetic and distinguish demonstration insights from verified facts.
5. For real-world conclusions, replace the generated data with reliable, cited data from authorised sources and update the report methodology.

## Limitations

- The dataset is synthetic and does not represent official Goa e-waste measurements.
- Fictional facility and registration identifiers do not establish that real facilities or authorisations exist.
- Environmental result labels and health-related fields are fabricated demonstration data, not evidence of pollution or medical conditions.
- Randomly generated values may not follow real-world statistical relationships.
- Any averages, comparisons, rankings, or trends derived from these records describe only the generated dataset.
- This dashboard is a demonstration/academic project, not a regulatory compliance or environmental-health decision tool.

## Suggested Project Description

**Goa E-Waste Intelligence Dashboard** is a data-visualisation project that demonstrates how e-waste generation, collection, recycling, compliance, informal-sector activity, environmental monitoring, and awareness-program information can be explored through an interactive dashboard and structured report. It uses a large synthetic dataset to demonstrate data filtering, charting, and reporting workflows.

## License and Attribution

No third-party data source is represented as the source of these synthetic records. Add an appropriate licence before publicly distributing the project, and cite any external datasets or libraries that you add in the future.
