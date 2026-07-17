# regulatory-data-quality-pipeline
# Automated Regulatory Data Quality (DQ) Pipeline

## Project Overview
This project simulates an automated data quality control engine designed for a financial institution. It ingests raw financial reporting streams and validates them against core data governance principles: Completeness, Validity, and Consistency.

## Key Features
- **Automated Exception Logging:** Scans and flags missing fields, invalid formats, and logical calculation anomalies.
- **KPI Metrics Generation:** Calculates a real-time "Data Health Score" (%) and summarizes systemic risks for stakeholder reporting.
- **Remediation Ready:** Automatically exports flagged data to an independent exceptions CSV file for rapid business remediation.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy
